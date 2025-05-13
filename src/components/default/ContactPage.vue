<script setup></script>

<template>
  <div class="p-4">
    <h1 class="text-2xl font-bold my-6">Contact</h1>
    <div class="grid md:grid-cols-3 gap-8">
      <!-- Address -->
      <div>
        <h2 class="text-xl font-extrabold mb-6 bg-white p-1 text-textPrimary">Address</h2>
        <div class="w-full h-40 md:h-60 mb-4 overflow-hidden">
          <div style="width: 100%">
            <iframe
              width="100%"
              height="600"
              frameborder="0"
              scrolling="no"
              marginheight="0"
              marginwidth="0"
              src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=vushtrri,Lutfi%20Musiqi+(My%20Business%20Name)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
            >
            </iframe>
          </div>
        </div>
        <p class="text-2xl text-textPrimary mt-10">Vushtrri</p>
        <p>42000</p>
      </div>

      <!-- Opening Hours -->
      <div>
        <h2 class="text-xl font-extrabold mb-6 bg-white p-1 text-textPrimary">Opening Hours</h2>
        <ul class="space-y-4">
          <li>Monday: 07:00 - 18:30</li>
          <li>Tuesday: 07:00 - 18:30</li>
          <li>Wednesday: 07:00 - 18:30</li>
          <li>Thursday: 07:00 - 18:30</li>
          <li>Friday: 07:00 - 18:30</li>
        </ul>
      </div>

      <!-- Contact -->
      <div>
        <h2 class="text-xl font-extrabold mb-6 bg-white p-1 text-textPrimary">Contact</h2>
        <p class="mb-3">Tel: +38344429579</p>
        <p>
          e-mail:
          <a href="mailto:shmt.lufti.musiqi@gmail.com"> lutfimusiqihighschool@gmail.com </a>
        </p>
      </div>
    </div>
  </div>
</template>
