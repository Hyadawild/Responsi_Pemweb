
<template>
  
 <link
  href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
  rel="stylesheet"
/>
<section class="about" data-aos="fade-up">
  <div class="container mx-auto">
    <div class="main-body">
      <div class="flex flex-wrap -mx-4">
        <div class="w-full md:w-1/3 px-4 mb-4">
          <div class="glass-effect shadow-lg rounded-lg p-4">
            <div class="flex flex-col items-center text-center">
              <img
                src="../assets/img/ara.png"
                alt="Admin"
                class="rounded-full w-full"
              />
              <div class="mt-3">
                <p>Hyadayada</p>
                <p class="text-gray-500 mb-1">Full Stack Developer eweww</p>
                <p class="text-gray-400">Bay Area, San Francisco, CA</p>
                <button class="btn btn-primary bg-blue-500 text-white px-4 py-2 rounded">Follow</button>
                <button class="btn btn-outline-primary border border-blue-500 text-blue-500 px-4 py-2 rounded mt-2">Message</button>
              </div>
            </div>
          </div>
          <div class="glass-effect shadow-lg rounded-lg p-4 mt-4">
            <ul class="divide-y divide-gray-200">
              <li class="flex justify-between items-center py-3">
                <h6 class="mb-0 flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-globe mr-2"
                  >
                    <circle cx="12" cy="12" r="10"></circle>
                    <line x1="2" y1="12" x2="22" y2="12"></line>
                    <path
                      d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"
                    ></path></svg
                  >Website
                </h6>
                <span class="text-gray-500">https://bootdey.com</span>
              </li>
              <li class="flex justify-between items-center py-3">
                <h6 class="mb-0 flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-github mr-2"
                  >
                    <path
                      d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
                    ></path></svg
                  >Github
                </h6>
                <span class="text-gray-500">bootdey</span>
              </li>
              <li class="flex justify-between items-center py-3">
                <h6 class="mb-0 flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-twitter mr-2 text-blue-500"
                  >
                    <path
                      d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
                    ></path></svg
                  >Twitter
                </h6>
                <span class="text-gray-500">@bootdey</span>
              </li>
              <li class="flex justify-between items-center py-3">
                <h6 class="mb-0 flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-instagram mr-2 text-red-500"
                  >
                    <rect
                      x="2"
                      y="2"
                      width="20"
                      height="20"
                      rx="5"
                      ry="5"
                    ></rect>
                    <path
                      d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"
                    ></path>
                    <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg
                  >Instagram
                </h6>
                <span class="text-gray-500">bootdey</span>
              </li>
              <li class="flex justify-between items-center py-3">
                <h6 class="mb-0 flex items-center">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    fill="none"
                    stroke="currentColor"
                    stroke-width="2"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    class="feather feather-facebook mr-2 text-blue-700"
                  >
                    <path
                      d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
                    ></path></svg
                  >Facebook
                </h6>
                <span class="text-gray-500">bootdey</span>
              </li>
            </ul>
          </div>
        </div>
        <div class="w-full md:w-2/3 px-4">
          <div class="glass-effect shadow-lg rounded-lg p-4 mb-4">
            <div>
              
              <hr />
              <div class="row mt-3">
                <div class="col-sm-3">
                  <h6 class="mb-0">Full Name</h6>
                </div>
                <div class="col-sm-9 text-gray-500">Haydar Wildan Zacky</div>
              </div>
              <hr />
              <div class="row">
                <div class="col-sm-3">
                  <h6 class="mb-0">Email</h6>
                </div>
                <div class="col-sm-9 text-gray-500">kiran@example.com</div>
              </div>
              <hr />
              <div class="row">
                <div class="col-sm-3">
                  <h6 class="mb-0">Phone</h6>
                </div>
                <div class="col-sm-9 text-gray-500">(239) 816-9029</div>
              </div>
              <hr />
              <div class="row">
                <div class="col-sm-3">
                  <h6 class="mb-0">Mobile</h6>
                </div>
                <div class="col-sm-9 text-gray-500">(320) 380-4539</div>
              </div>
              <hr />
              <div class="row">
                <div class="col-sm-3">
                  <h6 class="mb-0">Address</h6>
                </div>
                <div class="col-sm-9 text-gray-500">
                  Bay Area, San Francisco, CA
                </div>
              </div>
            </div>

            <div class="flex flex-wrap -mx-2 mt-4">
              <div class="w-full sm:w-1/2 px-2 mb-4">
                <div class="glass-effect shadow-lg rounded-lg p-4 h-full">
                  <h6 class="mb-3">Project Status</h6>
                  <small>Web Design</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 80%"
                    ></div>
                  </div>
                  <small>Website Markup</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 72%"
                    ></div>
                  </div>
                  <small>One Page</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 89%"
                    ></div>
                  </div>
                  <small>Mobile Template</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 55%"
                    ></div>
                  </div>
                  <small>Backend API</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 66%"
                    ></div>
                  </div>
                </div>
              </div>
              <div class="w-full sm:w-1/2 px-2 mb-4">
                <div class="glass-effect shadow-lg rounded-lg p-4 h-full">
                  <h6 class="mb-3">Project Status</h6>
                  <small>Web Design</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 80%"
                    ></div>
                  </div>
                  <small>Website Markup</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 72%"
                    ></div>
                  </div>
                  <small>One Page</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 89%"
                    ></div>
                  </div>
                  <small>Mobile Template</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5 mb-3">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 55%"
                    ></div>
                  </div>
                  <small>Backend API</small>
                  <div class="w-full bg-gray-200 rounded-full h-1.5">
                    <div
                      class="bg-blue-500 h-1.5 rounded-full"
                      style="width: 66%"
                    ></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
</template>

<script>
export default {
  name: 'AboutSection'
}

</script>

<style scoped>
.about {
  padding: 50px 0;
}

.glass-effect {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.3);
  }
</style>
