<template>
  <div class="navbar bg-base-100">
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

  <div class="bg-base-100">
    <div class="hero-content text-center">
      <div class="max-w-md">
        <h1 class="text-5xl font-bold">Hello there</h1>
        <p class="py-6">
          Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda
          excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a
          id nisi.
        </p>
      </div>
    </div>
  </div>

  <div class="flex justify-center">
    <input
      type="text"
      placeholder="Type here"
      class="input input-bordered w-full max-w-xs justify-center"
    />
  </div>
  <div class="flex justify-center">
    <div class="form-control">
      <label class="label cursor-pointer">
        <span class="label-text">Auto-Language</span>
        <input
          type="checkbox"
          class="toggle toggle-sm toggle-secondary"
          checked
        />
      </label>
    </div>
  </div>
</template>
