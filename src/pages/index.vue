<template>
        <!-- Content Area -->
        <main class="flex-1 overflow-y-auto p-4 bg-blue-50">
          <!-- Page Header -->
          <div class="flex items-center mb-6">
            <div class="bg-gray-800 p-2 rounded mr-4">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-6 w-6 text-white"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                />
              </svg>
            </div>
            <h1 class="text-2xl font-medium text-gray-800">
              Pengurusan Rekod Pembelajaran Dan Peperiksaan
            </h1>
          </div>
          <br>

          <div class="grid grid-cols-1 gap-4 px-4 mt-8 sm:grid-cols-4 sm:px-8 mb-4">
            <div class="flex items-center bg-white border rounded-sm overflow-hidden shadow">
                <div class="p-4 bg-green-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"></path>
                    </svg>
                </div>
                <div class="px-4 text-gray-700">
                    <h3 class="text-sm tracking-wider">Total Member</h3>
                    <p class="text-3xl">80</p>
                </div>
            </div>
            <div class="flex items-center bg-white border rounded-sm overflow-hidden shadow">
                <div class="p-4 bg-blue-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7v8a2 2 0 002 2h6M8 7V5a2 2 0 012-2h4.586a1 1 0 01.707.293l4.414 4.414a1 1 0 01.293.707V15a2 2 0 01-2 2h-2M8 7H6a2 2 0 00-2 2v10a2 2 0 002 2h8a2 2 0 002-2v-2"></path>
                    </svg>
                </div>
                <div class="px-4 text-gray-700">
                    <h3 class="text-sm tracking-wider">Total Attendance</h3>
                    <p class="text-3xl">68</p>
                </div>
            </div>
            <div class="flex items-center bg-white border rounded-sm overflow-hidden shadow">
                <div class="p-4 bg-indigo-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z"></path>
                    </svg>
                </div>
                <div class="px-4 text-gray-700">
                    <h3 class="text-sm tracking-wider">Total Permohonan</h3>
                    <p class="text-3xl">20</p>
                </div>
            </div>
            <div class="flex items-center bg-white border rounded-sm overflow-hidden shadow">
                <div class="p-4 bg-red-400">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4m0 5c0 2.21-3.582 4-8 4s-8-1.79-8-4"></path>
                    </svg>
                </div>
                <div class="px-4 text-gray-700">
                    <h3 class="text-sm tracking-wider">Total Penilaian</h3>
                    <p class="text-3xl">94%</p>
                </div>
            </div>
        </div>
        <br>
          <!-- Search Panel -->
          <div class="bg-off-white rounded-lg shadow p-6 mb-6">
            <div class="grid grid-cols-1 gap-4">
              <!-- Search Fields -->
              <div class="relative">
                <div
                  class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-gray-400"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </div>
                <input
                  type="text"
                  placeholder="No. Rujukan"
                  class="pl-10 pr-10 py-2 border border-gray-300 rounded-md w-full focus:outline-none focus:ring-1 focus:ring-blue-500"
                />
                <div class="absolute inset-y-0 right-0 flex items-center pr-3 text-gray-400">/</div>
              </div>

              <div class="relative">
                <div
                  class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-gray-400"
                >
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </div>
                <input
                  type="text"
                  placeholder="Tajuk Permohonan"
                  class="pl-10 pr-10 py-2 border border-gray-300 rounded-md w-full focus:outline-none focus:ring-1 focus:ring-blue-500"
                />
                <div class="absolute inset-y-0 right-0 flex items-center pr-3 text-gray-400">/</div>
              </div>

              <div>
                <label class="block text-sm text-gray-500 mb-1">Status Permohonan</label>
                <div class="relative">
                  <div
                    class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none text-gray-400"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-5 w-5"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M10 9a3 3 0 100-6 3 3 0 000 6zm-7 9a7 7 0 1114 0H3z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </div>
                  <select
                    class="pl-10 pr-10 py-2 border border-gray-300 rounded-md w-full appearance-none focus:outline-none focus:ring-1 focus:ring-blue-500"
                  >
                    <option>Semua</option>
                    <option>Aktif</option>
                    <option>Tidak Aktif</option>
                    <option>Selesai</option>
                    <option>Dibatalkan</option>
                  </select>
                  <div
                    class="absolute inset-y-0 right-0 flex items-center pr-3 pointer-events-none text-gray-400"
                  >
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="h-5 w-5"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </div>
                </div>
              </div>

              <!-- Action Buttons -->
              <div class="flex flex-wrap gap-2 mt-2">
                <button class="bg-indigo-500 hover:bg-indigo-600 text-white px-6 py-2 rounded-md">
                  CARI
                </button>
                <button class="bg-indigo-500 hover:bg-indigo-600 text-white px-6 py-2 rounded-md">
                  SET SEMULA
                </button>
                <button class="bg-indigo-500 hover:bg-indigo-600 text-white px-6 py-2 rounded-md">
                  PERMOHONAN BAHARU
                </button>
              </div>
            </div>
          </div>
       
        <br>
        <div class="grid grid-cols-2 gap-4 mt-4">
          <ApexChart 
            type="line" 
            height="350" 
            :options="chartOptions2" 
            :series="series2" 
          />
          <ApexChart 
            type="bar"
            height="350"
            :options="chartOptions"
            :series="series"
          />
        </div>
          <ApexChart 
            type="pie"
            height="350"
            :options="chartOptions3"
            :series="series3"
          />
          <br>

          <!-- Results Table -->
          <div class="bg-white rounded-lg shadow overflow-hidden">
              <table class="min-w-full divide-y divide-gray-200 border">
      <thead class="bg-gray-100">
        <tr>
          <th class="px-4 py-2 text-left">SL</th>
          <th class="px-4 py-2 text-left">Name</th>
          <th class="px-4 py-2 text-left">Date</th>
          <th class="px-4 py-2 text-left">Attendance</th>
        </tr>
      </thead>
      <tbody>
        <tr v-for="(item, index) in attendanceList" :key="item.id" class="bg-white hover:bg-gray-50">
          <td class="px-4 py-2">{{ index + 1 }}</td>
          <td class="px-4 py-2">{{ item.name }}</td>
          <td class="px-4 py-2">{{ item.date }}</td>
          <td class="px-4 py-2">{{ item.attendance }}</td>
        </tr>
      </tbody>
     
    </table>


          </div>
        </main>
</template>

<script setup lang="ts">


import { ref } from 'vue';
import axios from 'axios'
import { onMounted } from 'vue'

interface Attendance {
  id: number
  name: string
  date: string
  attendance: string
}

const attendanceList = ref<Attendance[]>([])

onMounted(async () => {
  try {
    const response = await axios.get('/api/attendance.json')
    attendanceList.value = response.data.data
  } catch (error) {
    console.log('error', error)
  }
})
const chartOptions = {
  labels: ['Team A', 'Team B', 'Team C', 'Team D', 'Team E'],
  responsive: [{
    breakpoint: 480,
    options: {
      chart: {
        width: 300
      },
      legend: {
        position: 'bottom'
      }
    }
  }],

  xaxis: {
    categories: ['Jan', 'Feb', 'Mar', 'Apr', 'May']
  },
  fill : {
    opacity: 1
  },
  chart: {
    height: 350,
    type: 'line',
    zoom: { enabled: false }
  },
  dataLabels: {
    enabled: false
  },
  stroke: {
    curve: 'smooth'
  },

  
}

const series = [
  {
  name: 'HRM',
  data: [30, 40, 45, 50, 49]
},
  {
  name: 'Late',
  data: [10, 25, 15, 5, 14]
},
  {
  name: 'Atttedance',
  data: [25, 30, 35, 40, 45]
}
];

const chartOptions2 = {
  labels: ['Team A', 'Team B', 'Team C', 'Team D', 'Team E'],
  responsive: [{
    breakpoint: 480,
    options: {
      chart: {
        width: 300
      },
      legend: {
        position: 'bottom'
      }
    }
  }],
  chart: {
    id: 'basic-bar'
  },
  xaxis: {
    categories: ['Jan', 'Feb', 'Mar', 'Apr', 'May']
  }
  
}

const series2 = [
  {
  name: 'HRM',
  data: [30, 40, 45, 50, 49]
},
  {
  name: 'Late',
  data: [10, 25, 15, 5, 14]
},
  {
  name: 'Atttedance',
  data: [25, 30, 35, 40, 45]
}
];
const chartOptions3 = {
  responsive: [{
    breakpoint: 480,
    options: {
      chart: {
        width: 300
      },
      legend: {
        position: 'bottom'
      }
    }
  }],
  chart: {
    id: 'basic-pie'
  },
  xaxis: {
    categories: ['Jan', 'Feb', 'Mar', 'Apr', 'May']
  }
  
}

const series3 = ref([44, 55, 13, 43, 22])


</script>

<style scoped></style>
