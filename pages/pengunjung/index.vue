<template>
  <div class="container">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
        <div class="my-3">
          <input type="search" class="form-control form-control-lg rounded-5" placeholder="fillter..." />
        </div>
        <div class="my-3 text-muted">menampilkan 1 dari 1</div>
        <table class="table">
          <thead>
            <tr>
              <td>NO</td>
              <td>NAMA</td>
              <td>KEANGGOTAAN</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1.</td>
              <td>ILHAM SH</td>
              <td>murid</td>
              <td>XI</td>
              <td>PPLG</td>
              <td>4</td>
              <td>224 februari 2024, 23.31.00</td>
              <td>Baca</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <NuxtLink to="/">
      <button type="button" class="btn btn-dark bck mt-5">Kembali</button>
    </NuxtLink>
  </div>
</template>
