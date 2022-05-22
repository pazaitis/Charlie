
<template>
<html data-theme="cupcake"></html>

  <div class="navbar bg-base-accent">
    <div class="flex-1">
      <a class="btn btn-ghost normal-case text-xl">Spellphabet</a>
    </div>
    <div class="flex-none">
      <ul class="menu menu-horizontal p-0">
        <li><a>Item 1</a></li>
        <li tabindex="0">
          <a>
            Parent
            <svg
              class="fill-current"
              xmlns="http://www.w3.org/2000/svg"
              width="20"
              height="20"
              viewBox="0 0 24 24"
            >
              <path
                d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z"
              />
            </svg>
          </a>
          <ul class="p-2 bg-base-100">
            <li><a>Submenu 1</a></li>
            <li><a>Submenu 2</a></li>
          </ul>
        </li>
        <li><a>Item 3</a></li>
      </ul>
    </div>
  </div>

  <div class="bg-base-accent">
    <div class="hero-content text-center">
      <div class="max-w-md">
        <h1 class="text-5xl font-bold">Just type and get it!</h1>
       
      </div>
  </div>
    </div>
<div class=" justify-center text-center ">
   <p class="py-6">
        Or just try examples
    </p>
    <button class="btn gap-2">
  <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 4v5h.582m15.356 2A8.001 8.001 0 004.582 9m0 0H9m11 11v-5h-.581m0 0a8.003 8.003 0 01-15.357-2m15.357 2H15" /></svg>
  Refresh
</button>


<a role="button" class="btn bg-accent">Link</a>
<button type="submit" class="btn bg-secondary-focus">Button</button>
<input type="button" value="Input" class="btn" />
<input type="submit" value="Submit" class="btn" />
<input type="reset" value="Reset" class="btn" />

</div>

<div class="form-control flex justify-center">
  <div class="input-group flex justify-center">
    <input type="text" placeholder="Type here" class="input input-bordered" />
    <button class="btn btn-square">
      <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" /></svg>
    </button>
  </div>
</div>

<div class="flex justify-center">
    <div class="form-control">
      <label class="label cursor-pointer">
        <span class="label-text">Auto-Language</span>
        <input
          type="checkbox"
          class="toggle toggle-sm toggle-accent"
          checked
        />
      </label>
    </div>
</div>

</template>
