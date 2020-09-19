<template>
    <div class="col-md-6">
        <div class="card">
            <div class="card-header">
                <h3 class="card-title">List Agenda</h3>
            </div>
            <div class="card-body">
                <div class="form-group">
                    <label for="">Hari</label>
                    <input type="text" v-model="agenda.hari" class="form-control" required>
                </div>
                <div class="form-group">
                    <label for="">Kegiatan</label>
                    <input type="text" v-model="agenda.kegiatan" class="form-control" required>
                </div>
                <div class="form-group">
<<<<<<< HEAD
                    <button class="btn btn-danger btn-sm" :disabled="isLoading" @click.prevent="simpan">{{ isLoading ? 'Loading...':'Tambahkan' }}</button>
=======
                    <button class="btn btn-danger btn-sm" @click.prevent="simpan">Tambahkan</button>
>>>>>>> 0024d994b7487b724d40625a738df9156c785843
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        name: 'AgendaInput',
        data() {
            return {
                agenda: {
                    hari: '',
                    kegiatan: ''
                }
            }
        },
<<<<<<< HEAD
	computed: {
		isLoading() {
		return this.$store.state.isLoading
		}
	},
        methods: {
            simpan() {
		this.$store.dispatch('simpanAgenda', this.agenda)
		this.agenda = {
		hari: '',
		kegiatan: ''
		}
=======
        methods: {
            simpan() {
		this.$store.dispatch('simpanAgenda', this.agenda)
	        this.agenda = {
        	hari: '',
        	kegiatan: ''
    		}
>>>>>>> 0024d994b7487b724d40625a738df9156c785843
            }
        }
    }
</script>
