<script>
  import light_bulb from "../assets/light_bulb.png";
  import dog from "../assets/dog.jpg";
</script>

<div class="p-6">
  <h2 class="text-white font-medium text-center text-3xl sm:text-4xl">
    Core Team:
  </h2>

  <ul class="flex items-center gap-10 sm:gap-20 w-fit mx-auto mt-8">
    <li class="flex flex-col items-center gap-4 text-white text-center">
      <img src={dog} alt="dog" class="rounded-full w-16 sm:w-20 h-16 sm:h-20" />
      <p>Lead Designer</p>
    </li>

    <li class="flex flex-col items-center gap-4 text-white text-center">
      <img
        src={light_bulb}
        alt="light_bulb"
        class="rounded-full w-16 sm:w-20 h-16 sm:h-20"
      />
      <p>Lead Developer</p>
    </li>
  </ul>
</div>
