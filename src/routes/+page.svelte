<script>
  import Button from "$lib/components/ui/button/button.svelte";
  import { ArrowRight } from "lucide-svelte";
</script>

<main class="flex flex-col">
  <section
    class=" flex flex-col gap-8 h-fit sm:gap-16 items-center sm:justify-center justify-start py-16 sm:min-h-screen outline"
  >
    <div class="flex items-center justify-center flex-col gap-2">
      <p class="font-sans font-medium text-base text-muted-foreground">
        your vision, captured prefectly
      </p>
      <p
        class="font-sans text-4xl sm:text-8xl leading-none tracking-wide font-semibold uppercase text-center"
      >
        brix vision
      </p>
    </div>
    <div
      class="flex *:capitalize justify-center items-center gap-6 max-w-md sm:w-screen"
    >
      <Button variant={"link"} size={"lg"}
        >Browse Gallery
        <ArrowRight class=" size-6" />
      </Button>
    </div>
  </section>
</main>
