<div class="flex flex-col bg-gray-200">
  <div class="fixed top-0 left-0 flex w-full items-center gap-4 bg-gradient-to-r from-emerald-200 via-sky-300 to-indigo-600 p-5 shadow-lg">
    <img
      class=" object-cover object-center"
      alt="logo"
      src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNi4xNTQiIGhlaWdodD0iMjcuMzY5IiB2aWV3Qm94PSIwIDAgMTYuMTU0IDI3LjM2OSI+CiAgICA8ZGVmcz4KICAgICAgICA8c3R5bGU+CiAgICAgICAgICAgIC5jbHMtMXtmaWxsOiMwMDgzZTN9CiAgICAgICAgPC9zdHlsZT4KICAgIDwvZGVmcz4KICAgIDxwYXRoIGlkPSJMb2dvIiBkPSJNMTI2NjAgNjEyNi4wMjF2LTguNTdsNy45NzktNC4zNjUgOC4xNzYgNC4zNjV2OC41N2wtOC4xNzYgNC4zNDl6bTIuMjk0LTEyLjAyMmExIDEgMCAxIDEgMSAxIDEgMSAwIDAgMS0xLjAwMS0uOTk5em05LTEuNWEuNS41IDAgMSAxIC41LjUuNS41IDAgMCAxLS41MDItLjQ5OXptLTUtNGExLjUgMS41IDAgMSAxIDEuNSAxLjUgMS41IDEuNSAwIDAgMS0xLjQ5OS0xLjQ5OXptMy00YS41LjUgMCAxIDEgLjUuNS41LjUgMCAwIDEtLjQ5OS0uNDk5em0tNC0uNWExIDEgMCAxIDEgMSAxIDEgMSAwIDAgMS0xLjAwMS0uOTk5eiIgY2xhc3M9ImNscy0xIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTI2NjAgLTYxMDMuMDAxKSIvPgo8L3N2Zz4K"
    />

    <h1 class="text-base tracking-normal">
      <strong class="hidden font-normal text-slate-700 lg:inline-flex">This Document is Issued on Blockchain by</strong>
      <strong class=" hidden font-semibold text-slate-900 lg:inline-flex">Print2Block</strong>
      powered by:
      <strong class="font-semibold text-sky-600 no-underline  hover:text-slate-900 hover:text-blue-800 hover:underline"><a href="https://print2block.com/" rel="noreferrer" target="_blank">DocChain.io</a></strong>
    </h1>
  </div>

  <div class="flex flex-col gap-4 py-28 lg:flex-row">
    <div class="order-2 flex w-full flex-col space-y-4 px-6 lg:order-none lg:block lg:w-3/5 ">
      <img class="h-full w-full overflow-hidden rounded-lg object-cover object-center" src="/assets/images/certificate1.jpeg" alt="document" />

      <div class="mx-auto flex items-center gap-4">
        <div class="flex h-11 w-11 items-center rounded-full border-2 border-sky-500 px-2 hover:scale-110 hover:bg-blue-500 lg:hidden">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class=" h-6 w-6 fill-sky-800 hover:fill-white">
            <path fill-rule="evenodd" d="M15.75 4.5a3 3 0 11.825 2.066l-8.421 4.679a3.002 3.002 0 010 1.51l8.421 4.679a3 3 0 11-.729 1.31l-8.421-4.678a3 3 0 110-4.132l8.421-4.679a3 3 0 01-.096-.755z" clip-rule="evenodd" />
          </svg>
        </div>

        <button class="mx-auto flex rounded-full  border-2 border-sky-500 py-2 px-6 text-base font-normal text-sky-600 hover:scale-110  hover:bg-blue-500 hover:text-white">Download</button>
      </div>
    </div>

    <div class="order-1 flex w-full flex-col gap-4 px-6  lg:order-none lg:w-2/5 ">
      <div class="flex h-52 w-full flex-col gap-4 rounded-lg bg-gradient-to-r from-indigo-400 via-purple-500 to-pink-400 p-4">
        <div class="order-2 flex gap-3 lg:order-none">
          <img class="h-24 w-24 overflow-hidden rounded object-cover object-center" src="/assets/images/qrcode.png" alt="qrcode" />
          <img class="h-24 w-24 overflow-hidden rounded object-cover object-center" src="/assets/images/logo.jpeg" alt="logo" />

          <div class="flex flex-col gap-10 lg:hidden">
            <button value="1" onclick="select(value)" class="flex  rounded-full border-2 border-white px-3 py-1 text-xs font-medium text-white">VIEW INFO</button>
            <button class="flex  rounded-full border-2 border-white px-6 py-1 text-xs font-medium uppercase text-white ">Verify</button>
          </div>
        </div>
        <div class="order-1 flex flex-col lg:order-none">
          <h1 class="mt-2 text-base font-normal text-white">SIDBI (DEMO)</h1>
          <h1 class="text-lg font-bold text-white">Fixed Deposit Report</h1>
        </div>
      </div>

      <div class=" hidden space-y-3 px-4 py-2 lg:block">
        <div>
          <h1 class="text-base font-normal text-slate-700">Issuer</h1>
          <h1 class="text-lg font-normal text-slate-900">SIDBI (DEMO)</h1>
        </div>
        <div>
          <h1 class="text-base font-normal text-slate-700">Date Published</h1>
          <h1 class="text-lg font-normal tracking-wide text-slate-900">Wed Aug 17 2022 22:49:04 GMT+0530 (India Standard Time)</h1>
        </div>
        <div>
          <h1 class="text-base font-normal text-slate-700">Published TXID</h1>
          <p class="break-all text-lg font-normal leading-relaxed tracking-normal text-slate-900">
            {txid}
          </p>
        </div>
        <div>
          <h1 class="text-base font-normal text-slate-700">Data Hash (SHA256)</h1>
          <p class="break-all text-lg font-normal leading-relaxed tracking-normal text-slate-900">
            {dataHash}
          </p>
        </div>
        <div>
          <h1 class="text-base font-normal text-slate-700">File Hash (SHA256)</h1>
          <p class="break-all text-lg font-normal leading-relaxed tracking-normal text-slate-900">
            {fileHash}
          </p>
        </div>

        <button class="mx-auto mt-4 hidden  rounded-full border-2 border-sky-300 bg-sky-500 py-1 px-6 text-lg font-normal text-white lg:block">Verify</button>
      </div>
    </div>
  </div>

  <footer class="flex-1 border-2 border-slate-200 text-center">
    <h1 class="pb-5  text-base font-normal text-slate-900">
      All rights reserved.<a class="font-semibold text-sky-600 no-underline hover:text-sky-900 hover:underline" href="https://print2block.com/"> Print2Block © 2018-2022 </a>
    </h1>
  </footer>
</div>
