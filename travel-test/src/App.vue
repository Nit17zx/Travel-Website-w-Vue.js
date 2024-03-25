<template>
  <div class="flex flex-col min-h-screen">
    <header class="h-14 flex items-center">
      <div class="container flex items-center px-4 md:px-6">
        <router-link class="flex items-center justify-center" to="/">
          <SunsetIcon class="h-6 w-6" />
          <span class="sr-only">Travel Vibes</span>
        </router-link>
        <nav class="ml-auto hidden lg:flex gap-4 lg:gap-6">
          <router-link class="text-sm font-medium hover:underline underline-offset-4" to="/flights">
            Flights
          </router-link>
          <router-link class="text-sm font-medium hover:underline underline-offset-4" to="/hotels">
            Hotels
          </router-link>
          <router-link class="text-sm font-medium hover:underline underline-offset-4" to="/activities">
            Activities
          </router-link>
        </nav>
        <div class="ml-auto flex items-center gap-4 lg:gap-6">
          <router-link class="text-sm font-medium hover:underline underline-offset-4" to="/signin">
            Sign In
          </router-link>
          <Button variant="outline">Sign Up</Button>
        </div>
      </div>
    </header>
    <main class="flex-1">
      <section class="w-full py-12 md:py-24 lg:py-32 xl:py-48">
        <div class="container flex flex-col items-center justify-center px-4 space-y-4 md:px-6">
          <div class="space-y-2 text-center">
            <h1 class="text-4xl font-bold tracking-tighter sm:text-5xl md:text-6xl">
              Discover your next adventure
            </h1>
            <p class="mx-auto max-w-[600px] text-gray-500/relaxed md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed dark:text-gray-400/relaxed">
              Find the best deals on flights, hotels, and activities. Enter your destination below.
            </p>
          </div>
          <div class="w-full max-w-sm space-y-2">
            <form class="grid gap-4">
              <div class="grid gap-1.5">
                <Label class="text-sm" for="destination">
                  Enter your destination
                </Label>
                <Input class="w-full" id="destination" placeholder="Where are you going?" />
              </div>
              <div class="grid gap-1.5">
                <Label class="text-sm" for="check-in">
                  Check-in
                </Label>
                <Input class="w-full" id="check-in" type="date" />
              </div>
              <Button class="w-full" type="submit">
                Search
              </Button>
            </form>
          </div>
        </div>
      </section>
      <section class="w-full py-12 md:py-24 lg:py-32 border-t">
        <div class="container grid items-center gap-4 px-4 md:px-6">
          <div class="space-y-2">
            <h2 class="text-3xl font-bold tracking-tighter sm:text-4xl md:text-5xl">Popular Destinations</h2>
            <p class="max-w-[600px] text-gray-500 md:text-xl/relaxed lg:text-base/relaxed xl:text-xl/relaxed dark:text-gray-400">
              Discover the most popular destinations. These are the places that everyone is talking about.
            </p>
          </div>
          <div class="grid w-full grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 items-start gap-6 md:gap-4 lg:gap-8">
            <!-- Cards go here -->
          </div>
        </div>
      </section>
    </main>
    <footer class="flex flex-col gap-2 sm:flex-row py-6 w-full shrink-0 items-center px-4 md:px-6 border-t">
      <p class="text-xs text-gray-500 dark:text-gray-400">© 2024 Travel Vibes. All rights reserved.</p>
      <nav class="sm:ml-auto flex gap-4 sm:gap-6">
        <router-link class="text-xs hover:underline underline-offset-4" to="/about">
          About Us
        </router-link>
        <router-link class="text-xs hover:underline underline-offset-4" to="/contact">
          Contact
        </router-link>
        <router-link class="text-xs hover:underline underline-offset-4" to="/terms">
          Terms & Conditions
        </router-link>
      </nav>
    </footer>
  </div>
</template>

<script>
import { Button } from "@/components/ui/button.vue";
import { Label } from "@/components/ui/label.vue";
import { Input } from "@/components/ui/input.vue";
import { CardContent, Card } from "@/components/ui/card.vue";

export default {
  components: {
    Button,
    Label,
    Input,
    CardContent,
    Card,
  },
};
</script>

<style scoped>
/* Your styles here */
</style>
