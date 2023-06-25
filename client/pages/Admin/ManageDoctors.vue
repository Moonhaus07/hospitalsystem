<template>
    <div class="flex h-screen">
        <AdminSidebar />
        <main class="bg-gray-100 flex-1 p-4">

            <div class="p-8 my-4">
                <h2 class="font-semibold text-2xl">Welcome Admin!</h2>
            </div>

            <div class="p-4">
                <div class="grid grid-cols-2 gap-4 mb-4">

                    <div class="mx-2 grid grid-cols-2 gap-72 ">
                        <h3 class="font-semibold">Doctors Available</h3>
                        <NuxtLink to="/Admin/AddNewDoctor"><button class="bg-white rounded-lg shadow-md p-1">+ Add New
                                Doctor</button>
                        </NuxtLink>
                    </div>

                </div>
                <div class="grid grid-cols-2 gap-4 mb-4">

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

                    <Tables />

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