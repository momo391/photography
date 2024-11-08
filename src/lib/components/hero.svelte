<script>
  import Button from "$lib/components/ui/button/button.svelte";
  import ArrowUpRight from "@tabler/icons-svelte/icons/arrow-up-right";
</script>

<section class="relative min-h-screen">
  <div class="absolute inset-0 flex items-center justify-center flex-col gap-8">
    <div class="flex items-center justify-center flex-col gap-2">
      <p class="font-sans font-bold text-base text-muted-foreground">
        your vision, perfectly captured
      </p>
      <p
        class="font-sans text-5xl sm:text-6xl md:text-7xl lg:text-9xl leading-none tracking-wide font-semibold uppercase text-center"
      >
        brix vision
      </p>
    </div>
    <div
      class="flex flex-col sm:flex-row *:capitalize justify-center items-center gap-4 max-w-md sm:w-screen"
    >
      <Button variant={"default"} size={"lg"}>get in touch</Button>
    </div>
  </div>
  <div class=" absolute bottom-0 inset-x-0 flex items-center justify-end gap-2">
    <Button variant={"link"} size={"sm"}
      >facebook
      <ArrowUpRight class=" size-4" />
    </Button>
    <Button variant={"link"} size={"sm"}
      >instagram
      <ArrowUpRight class=" size-4" />
    </Button>
  </div>
  <img
    src={"https://utfs.io/f/8uPOhORkQcG5BRCj5hKY94aFJTsXrUbwIq1ZMm2Vxg0puBPn"}
    alt="background"
    class="absolute inset-0 -z-20 w-screen h-screen object-cover bg-fixed"
  />

  <div class="absolute inset-0 -z-10 bg-black opacity-50"></div>
</section>

<!-- <Button variant={"link"} size={"lg"}
  >get in touch
  <ArrowRight class=" size-6" />
</Button> -->
