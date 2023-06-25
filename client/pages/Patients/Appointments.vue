<template>
    <div class="flex h-screen">
        <PatientsSidebar />
        <main class="bg-gray-100 flex-1 p-4">

            <div class="p-8 my-4">
                <h2 class="font-semibold text-2xl">Welcome Mr. Patient!</h2>
            </div>

            <div class="p-4">
                <div class="grid grid-cols-2 gap-4 mb-4">
                    <div class="mx-2 grid grid-cols-2 gap-72 ">
                        <h3 class="font-semibold">Appointments </h3>
                        <button class="bg-white rounded-lg shadow-md ">+ Add New Appointment</button>
                    </div>

                </div>
                <div class="grid grid-cols-2 gap-4 mb-4">
                    <div class="bg-white rounded-lg shadow-md p-4 justify-center">
                        <h2 class="text-lg font-semibold pb-4">Appointment No: 10001 </h2>

                        <h2 class="text-md ">Date : <span id="Name" class="font-semibold"> July</span> </h2>
                        <h2 class="text-md ">Time : <span id="time" class="font-semibold"> 9:00 am</span> </h2>
                        <h2 class="text-md ">Room : <span id="roomNo" class="font-semibold"> 301</span></h2>
                        <h2 class="text-md ">Doctor : <span id="doctorname" class="font-semibold"> Vince</span></h2>
                        
                    </div>

                    <div>

                    </div>
                    <div class="pb-24">

                    </div>

                </div>
                <div class="mx-4 pb-2">
                    <h3 class="font-semibold">Appointments History</h3>
                </div>
                <div class="h-48 mb-4">

                    <PatientsPTables />

                </div>

            </div>


        </main>
    </div>
</template>
  
<script>
export default {
    layout: 'vertical-dashboard',
}




</script>