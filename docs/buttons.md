# Buttons


### Basic

<div class="flex w-full text-center py-16">
  <div class="flex-grow">
    <button class="rounded bg-gray-100 text-gray-700 px-4 py-2 hover:bg-gray-200">
      Default
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded bg-blue-500 text-white px-4 py-2 hover:bg-blue-600">
      Primary
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded bg-green-500 text-white px-4 py-2 hover:bg-green-600">
      Success
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded bg-yellow-500 text-white px-4 py-2 hover:bg-yellow-600">
      Warning
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded bg-red-500 text-white px-4 py-2 hover:bg-red-600">
      Danger
    </button>
  </div>
</div>

<details class="border border-gray-300 rounded-md px-4">
  <summary class="text-center font-bold cursor-pointer focus:outline-none py-2">Show Code</summary>

  ```html
  <!-- Default Button -->
  <button class="rounded bg-gray-100 text-gray-700 px-4 py-2 hover:bg-gray-200">
    Default
  </button>

  <!-- Primary Button -->
  <button class="rounded bg-blue-500 text-white px-4 py-2 hover:bg-blue-600">
    Primary
  </button>

  <!-- Success Button -->
  <button class="rounded bg-green-500 text-white px-4 py-2 hover:bg-green-600">
    Success
  </button>

  <!-- Warning Button -->
  <button class="rounded bg-yellow-500 text-white px-4 py-2 hover:bg-yellow-600">
    Warning
  </button>

  <!-- Danger Button -->
  <button class="rounded bg-red-500 text-white px-4 py-2 hover:bg-red-600">
    Danger
  </button>
  ```
</details>

### Outlined

<div class="flex w-full text-center py-16">
  <div class="flex-grow">
    <button class="rounded border border-gray-400 text-gray-700 px-4 py-2 hover:bg-gray-400">
      Default
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded border border-blue-500 text-blue-500 hover:text-white px-4 py-2 hover:bg-blue-500">
      Primary
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded border border-green-500 text-green-500 hover:text-white px-4 py-2 hover:bg-green-500">
      Success
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded border border-yellow-500 text-yellow-500 hover:text-white px-4 py-2 hover:bg-yellow-500">
      Warning
    </button>
  </div>
  <div class="flex-grow">
    <button class="rounded border border-red-500 text-red-500 hover:text-white px-4 py-2 hover:bg-red-500">
      Danger
    </button>
  </div>
</div>

<details class="border border-gray-300 rounded-md px-4">
  <summary class="text-center font-bold cursor-pointer focus:outline-none py-2">Show Code</summary>

  ```html
  <!-- Default Button -->
  <button class="rounded border border-gray-400 text-gray-700 px-4 py-2 hover:bg-gray-400">
    Default
  </button>

  <!-- Primary Button -->
  <button class="rounded border border-blue-500 text-blue-500 hover:text-white px-4 py-2 hover:bg-blue-500">
    Primary
  </button>

  <!-- Success Button -->
  <button class="rounded border border-green-500 text-green-500 hover:text-white px-4 py-2 hover:bg-green-500">
    Success
  </button>

  <!-- Warning Button -->
  <button class="rounded border border-yellow-500 text-yellow-500 hover:text-white px-4 py-2 hover:bg-yellow-500">
    Warning
  </button>

  <!-- Danger Button -->
  <button class="rounded border border-red-500 text-red-500 hover:text-white px-4 py-2 hover:bg-red-500">
    Danger
  </button>
  ```
</details>

### Advanced
Rounded version of basic and outlined buttons with transition

<div class="flex w-full text-center py-16 rounded-t-md">
  <div class="flex-grow">
    <button class="transition duration-500 ease-in-out rounded bg-blue-500 text-white px-4 py-2 hover:bg-blue-600">
      Basic button
    </button>
  </div>
  <div class="flex-grow">
    <button class="transition duration-500 ease-in-out rounded-full bg-blue-500 text-white px-4 py-2 hover:bg-blue-600">
      Basic rounded button 
    </button>
  </div>
  <div class="flex-grow">
    <button class="transition duration-500 ease-in-out rounded border border-blue-500 text-blue-500 hover:text-white px-4 py-2 hover:bg-blue-500">
      Outlined button
    </button>
  </div>
  <div class="flex-grow">
    <button class="transition duration-500 ease-in-out rounded-full border border-blue-500 text-blue-500 hover:text-white px-4 py-2 hover:bg-blue-500">
      Outlined rounded button
    </button>
  </div>
</div>

<details class="border border-gray-300 rounded-md px-4">
  <summary class="text-center font-bold cursor-pointer focus:outline-none py-2">Show Code</summary>

  ```html
  <!-- Basic Button  -->
  <button class="transition duration-500 ease-in-out rounded bg-blue-500 text-white px-4 py-2 hover:bg-blue-600">
    Basic button
  </button>

  <!-- Basic Rounded Button  -->
  <button class="transition duration-500 ease-in-out rounded-full bg-blue-500 text-white px-4 py-2 hover:bg-blue-600">
    Basic rounded button 
  </button>
  
  <!-- Outlined Button  -->
  <button class="transition duration-500 ease-in-out rounded border border-blue-500 text-blue-500 hover:text-white px-4 py-2 hover:bg-blue-500">
    Outlined button
  </button>
  
  <!-- Outlined Rounded Button  -->
  <button class="transition duration-500 ease-in-out rounded-full border border-blue-500 text-blue-500 hover:text-white px-4 py-2 hover:bg-blue-500">
    Outlined rounded button
  </button>
  ```
</details>