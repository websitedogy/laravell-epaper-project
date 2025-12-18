<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<script src="https://cdn.tailwindcss.com"></script>
<title>Director Bank Details</title>
</head>

<body class="bg-gray-100 p-6">

<div class="max-w-4xl mx-auto bg-white shadow-2xl rounded-2xl p-10">

  <h1 class="text-3xl font-bold text-purple-700 mb-8">Director Bank Details & NOC</h1>

  <!-- ================= DIRECTOR 1 ================= -->
  <h2 class="text-xl font-semibold text-purple-600 mb-4">Director 1 – Bank Details</h2>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-10">

    <div>
      <label class="font-medium">Bank Holder Name</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="Director Name">
    </div>

    <div>
      <label class="font-medium">Account Number</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="Account Number">
    </div>

    <div>
      <label class="font-medium">IFSC Code</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="IFSC Code">
    </div>

    <div>
      <label class="font-medium">Bank Name</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="Bank Name">
    </div>

    <div class="md:col-span-2">
      <label class="font-medium">Upload Bank Statement (Last 6 Months)</label>
      <input type="file" class="block mt-1">
    </div>

  </div>


  <!-- ================= DIRECTOR 2 ================= -->
  <h2 class="text-xl font-semibold text-purple-600 mb-4">Director 2 – Bank Details</h2>

  <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-10">
    <div>
      <label class="font-medium">Bank Holder Name</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="Director Name">
    </div>

    <div>
      <label class="font-medium">Account Number</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="Account Number">
    </div>

    <div>
      <label class="font-medium">IFSC Code</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="IFSC Code">
    </div>

    <div>
      <label class="font-medium">Bank Name</label>
      <input class="w-full mt-1 p-3 border rounded-lg" placeholder="Bank Name">
    </div>

    <div class="md:col-span-2">
      <label class="font-medium">Upload Bank Statement (Last 6 Months)</label>
      <input type="file" class="block mt-1">
    </div>
  </div>


  <!-- ================= FINAL NOC ================= -->
  <h2 class="text-xl font-semibold text-purple-600 mb-4">Final Company NOC Upload</h2>

  <div class="mb-10">
    <label class="font-medium">Upload NOC (Owner / Director Permission Letter)</label>
    <input type="file" class="block mt-1">
  </div>
  <div class="mb-10">
    <label class="font-medium">Upload NOC (Owner / Director Permission Letter)</label>
    <input type="file" class="block mt-1">
  </div>
  <div class="mb-10">
    <label class="font-medium">Upload NOC (Owner / Director Permission Letter)</label>
    <input type="file" class="block mt-1">
  </div>

  <button class="w-full bg-purple-600 text-white text-lg py-3 rounded-xl">
    Submit
  </button>

</div>

</body>
</html>


