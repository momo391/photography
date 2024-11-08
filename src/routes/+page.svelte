<script>
  import Hero from "$lib/components/hero.svelte";
  import { Button } from "$lib/components/ui/button";
  import ArrowUpRight from "@tabler/icons-svelte/icons/arrow-up-right";
</script>

<main class="flex flex-col">
  <Hero />
  <section>
    <div>
      <p>about us</p>
      <p>black vision is a full service production company</p>
      <Button variant={"link"}>
        more about us
        <ArrowUpRight class=" size-4" />
      </Button>
    </div>
    <div>
      <img src="" alt="about us" />
    </div>
  </section>
</main>
<footer class="w-full h-8 flex items-center justify-center py-2 mt-8">
  <p class="font-sans font-medium text-base text-muted-foreground">
    by momo391 and walid aissani
  </p>
</footer>
