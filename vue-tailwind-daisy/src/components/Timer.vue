<template>
  <div class="grid auto-cols-max grid-flow-col gap-5 text-center">
    <div class="flex flex-col">
      <span class="countdown font-mono text-5xl">
        <span style="--value: 15" aria-live="polite" aria-label="15">15</span>
      </span>
      days
    </div>
    <div class="flex flex-col">
      <span class="countdown font-mono text-5xl">
        <span style="--value: 10" aria-live="polite" aria-label="10">10</span>
      </span>
      hours
    </div>
    <div class="flex flex-col">
      <span class="countdown font-mono text-5xl">
        <span style="--value: 24" aria-live="polite" aria-label="24">24</span>
      </span>
      min
    </div>
    <div class="flex flex-col">
      <span class="countdown font-mono text-5xl">
        <span style="--value: 59" aria-live="polite" aria-label="59">59</span>
      </span>
      sec
    </div>
  </div>
</template>

<script>
export default {
  name: "Timer",
};
</script>
