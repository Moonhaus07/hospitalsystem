<template>
  <div class="flex h-screen">
    <PatientsSidebar/>
    <main class="bg-gray-100 flex-1 p-4">

      <div class="p-8 my-4">
        <h2 class="font-semibold text-2xl">Welcome Mr. Patient!</h2>
      </div>

      <div class="p-4">
        <div class="grid grid-cols-2 gap-4 mb-4">
          <div class="mx-4 pb-2">
            <h3 class="font-semibold">Upcoming Appointments</h3>
          </div>
          <div class="mx-4 pb-2">
            <h3 class="font-semibold">Doctors Available</h3>
          </div>
        </div>
        <div class="grid grid-cols-2 gap-4 mb-4">
          <div class="bg-white rounded-lg shadow-md p-4 justify-center">
            <h2 class="text-lg font-semibold">Appointment Info: B34 </h2>
          </div>
          <div class="bg-white rounded-lg shadow-md p-4 justify-center">
            <DoctorDTables />
          </div>
          <div>

          </div>
          <div>

          </div>

        </div>
        <div class="mx-4 pb-2">
          <h3 class="font-semibold">Upcoming Appointments</h3>
        </div>
        <div class="h-48 mb-4">

          <PatientsPTables/>

        </div>

      </div>



      <!-- 
      <div class="p-8 my-12">
        <h2 class="font-semibold text-2xl">Welcome Mr. Patient!</h2>
      </div>

      <div class="mx-4">
        <h3 class="font-semibold">Upcoming Appointments</h3>
      </div>
      <div class="grid grid-cols-3 gap-4 p-4">
        <div class="bg-white rounded-lg shadow-md p-4">
          <h2 class="text-lg font-semibold">Appointment Info:  </h2>      
        </div>
        
        <div class="mx-4">
          <div class="bg-white rounded-lg shadow-md p-4">
          <h2 class="text-lg font-semibold">acc info here</h2>
          <p>patient info here</p>
        </div>
        </div>
      </div>
      
      <div class="mx-4">
        <h3 class="font-semibold">Appointment Records</h3>
      </div>
      <div class="bg-white rounded-lg shadow-md p-4">
        <h2 class="text-lg font-semibold">records here</h2>
        <p>info here</p>
      </div> -->
    </main>
  </div>
</template>

<script>
export default {
  layout: 'vertical-dashboard',
}
</script>