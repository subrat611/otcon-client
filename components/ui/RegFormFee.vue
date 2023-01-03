<template>
  <div>
    <ui-navbar></ui-navbar>
    <div class="container mt-4">
      <div class="row">
        <div class="col">
          <h4>Registration Fee</h4>
        </div>
        <div class="col-12 mt-3">
          <table class="table">
            <thead>
              <tr class="table-primary">
                <th scope="col" colspan="5" class="text-end">
                  Early Bird (30<sup>th</sup> Nov, 2022)
                </th>
              </tr>
              <tr class="table-warning">
                <th>Category</th>
                <th colspan="2">Active IEEE member</th>
                <th colspan="2">Non IEEE member</th>
              </tr>
              <tr class="table-light">
                <th>(Author)</th>
                <th>INR</th>
                <th>USD</th>
                <th>INR</th>
                <th>USD</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Full-time student/Research scholar</td>
                <td>₹4000<br /><span class="text-danger">+18% GST</span></td>
                <td>$75<br /><span class="text-danger">+18% GST</span></td>
                <td>₹5000<br /><span class="text-danger">+18% GST</span></td>
                <td>$80<br /><span class="text-danger">+18% GST</span></td>
              </tr>
              <tr>
                <td>Academician</td>
                <td>₹5000<br /><span class="text-danger">+18% GST</span></td>
                <td>$80<br /><span class="text-danger">+18% GST</span></td>
                <td>₹6000<br /><span class="text-danger">+18% GST</span></td>
                <td>$90<br /><span class="text-danger">+18% GST</span></td>
              </tr>
              <tr>
                <td>Industry</td>
                <td>₹7000<br /><span class="text-danger">+18% GST</span></td>
                <td>$110<br /><span class="text-danger">+18% GST</span></td>
                <td>₹8000<br /><span class="text-danger">+18% GST</span></td>
                <td>$125<br /><span class="text-danger">+18% GST</span></td>
              </tr>
              <tr>
                <td></td>
                <td colspan="4" class="table-primary text-end fw-bold">
                  Regular (31<sup>st</sup> Jan, 2023)
                </td>
              </tr>
              <tr>
                <td>Full-time Student/Research Scholar</td>
                <td>₹6000<br /><span class="text-danger">+18% GST</span></td>
                <td>$90<br /><span class="text-danger">+18% GST</span></td>
                <td>₹7000<br /><span class="text-danger">+18% GST</span></td>
                <td>$110<br /><span class="text-danger">+18% GST</span></td>
              </tr>
              <tr>
                <td>Academician</td>
                <td>₹7000<br /><span class="text-danger">+18% GST</span></td>
                <td>$110<br /><span class="text-danger">+18% GST</span></td>
                <td>₹8000<br /><span class="text-danger">+18% GST</span></td>
                <td>$125<br /><span class="text-danger">+18% GST</span></td>
              </tr>
              <tr>
                <td>Industry</td>
                <td>₹9000<br /><span class="text-danger">+18% GST</span></td>
                <td>$130<br /><span class="text-danger">+18% GST</span></td>
                <td>₹10000<br /><span class="text-danger">+18% GST</span></td>
                <td>$140<br /><span class="text-danger">+18% GST</span></td>
              </tr>
              <tr>
                <td>Participants/Extra authors/Listener</td>
                <td colspan="4" class="text-center">
                  ₹2000 <span class="text-danger">+18% GST</span>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@media (max-width: 430px) {
  .table {
    font-size: 11px;
  }
}

@media (max-width: 280px) {
  .table {
    font-size: 8px;
  }
}
</style>
