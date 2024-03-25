<template>
  <div class="flex flex-col justify-center bg-white">
    <div class="p-14 w-full bg-gray-200 max-md:px-5 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col max-md:gap-0">
        <div class="flex flex-col w-[74%] max-md:ml-0 max-md:w-full">
          <header class="flex flex-col grow w-full bg-white rounded-2xl max-md:mt-10 max-md:max-w-full">
            <nav class="flex flex-col justify-center px-16 py-4 bg-white max-md:px-5 max-md:max-w-full">
              <div class="flex gap-5 justify-between w-full max-md:flex-wrap max-md:max-w-full">
                <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/66a16d49b6fe79475af6bfb26d2099464df99952832d8000ba07b7024f162da3?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Company Logo" class="shrink-0 self-start max-w-full aspect-[5.56] w-[130px]" />
                <div class="flex gap-5 justify-between">
                  <div class="flex gap-5 justify-between my-auto text-xs whitespace-nowrap text-neutral-700">
                    <a href="#" class="text-sky-700">Explore</a>
                    <a href="#">Search</a>
                    <a href="#">Hotels</a>
                    <a href="#">Offers</a>
                  </div>
                  <div class="flex gap-2.5 justify-between">
                    <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/5b2c2fd96cf7581aa2641ff78611bf65c59e0f4d92c74221370aebcd1bbca04d?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Notification Icon" class="shrink-0 my-auto aspect-square w-[18px]" />
                    <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/a88e5e6c6d30b3082cab182350fc608edb25fe6dbcfc52439e3a73f44cc90d7b?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="User Avatar" class="shrink-0 px-3 py-2.5 aspect-[1.04] w-[27px]" />
                  </div>
                </div>
              </div>
            </nav>
            <section class="flex flex-col justify-center max-md:max-w-full">
              <div class="flex overflow-hidden relative flex-col justify-center w-full min-h-[478px] max-md:max-w-full">
                <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/6bb5dfd584e0af7e74a7a20ee1219203a6887dc7cc142d34cdd45e2d2a6e91b2?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Hero Background" class="object-cover absolute inset-0 size-full" />
                <div class="flex relative justify-center items-center px-16 py-20 max-md:px-5 max-md:max-w-full">
                  <div class="flex flex-col mt-16 mb-9 max-w-full w-[867px] max-md:mt-10">
                    <h1 class="text-5xl text-center text-white leading-[50.6px] max-md:max-w-full max-md:text-4xl">
                      Let's explore &amp; travel the world
                    </h1>
                    <p class="mt-1 text-lg leading-6 text-center text-white max-md:max-w-full">
                      Find the best destinations and the most popular stays!
                    </p>
                    <form class="flex gap-1 p-4 mt-8 bg-white rounded-lg max-md:flex-wrap">
                      <div class="flex flex-1 gap-2 p-1 tracking-normal max-md:flex-wrap">
                        <div class="flex flex-col px-2.5 pb-3 rounded-sm border border-solid border-black border-opacity-20">
                          <label for="departure" class="justify-center px-1 text-xs leading-loose whitespace-nowrap bg-white text-black text-opacity-60">Departure</label>
                          <input type="text" id="departure" name="departure" value="Singapore (SIN)" class="mt-3 text-xs leading-5 text-black text-opacity-90" />
                        </div>
                        <div class="flex flex-col px-2.5 pb-3 rounded-sm border border-solid border-black border-opacity-20">
                          <label for="arrival" class="justify-center px-1 text-xs leading-loose whitespace-nowrap bg-white text-black text-opacity-60">Arrival</label>
                          <input type="text" id="arrival" name="arrival" value="Los Angeles (LA)" class="mt-3 text-xs leading-5 text-black text-opacity-90" />
                        </div>
                        <div class="flex flex-col px-2.5 whitespace-nowrap rounded-sm border border-solid border-black border-opacity-20">
                          <label for="date" class="justify-center px-1 text-xs leading-loose bg-white text-black text-opacity-60">Date</label>
                          <div class="flex gap-1.5 py-3 text-xs leading-5 text-black text-opacity-90">
                            <input type="text" id="date" name="date" value="01/05/2022" class="flex-1" />
                            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/4c2bfcf5b220d442e56803174ccaa3d4111bf5ee83f6b63a2c3163d1b2b09372?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Calendar Icon" class="shrink-0 aspect-square w-[18px]" />
                          </div>
                        </div>
                      </div>
                      <button type="submit" class="justify-center px-1.5 py-3 my-auto text-xs font-medium tracking-wide leading-5 text-center text-white uppercase bg-amber-500 rounded-sm">
                        Search flights
                      </button>
                    </form>
                  </div>
                </div>
              </div>
            </section>
          </header>
          <section class="flex flex-col px-16 pb-5 mt-14 max-md:px-5 max-md:mt-10 max-md:max-w-full">
            <h2 class="text-sm font-bold tracking-wide uppercase text-zinc-800 max-md:max-w-full">Upcoming Flight</h2>
            <div class="py-px mt-4 max-md:max-w-full">
              <div class="flex gap-5 max-md:flex-col max-md:gap-0">
                <div class="flex flex-col w-[27%] max-md:ml-0 max-md:w-full">
                  <div class="flex flex-col grow p-4 rounded-md border border-gray-200 border-solid max-md:mt-10">
                    <div class="flex gap-1.5 justify-between capitalize">
                      <div class="flex flex-col py-0.5 whitespace-nowrap">
                        <div class="text-lg font-bold tracking-wider text-sky-700">SIN</div>
                        <div class="mt-2 text-xs tracking-wide text-neutral-400">Singapore</div>
                      </div>
                      <div class="flex flex-col items-center self-start py-px text-xs font-bold tracking-wide text-neutral-400">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/b8f885b98aa70d056ee2f1483dce2a6a1e33242fafff98beb5e4ce8ad830bafa?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Flight Duration" class="aspect-[5] w-[88px]" />
                        <div class="mt-1.5">15H 55M</div>
                      </div>
                      <div class="flex flex-col py-0.5 text-right">
                        <div class="text-lg font-bold tracking-wider text-sky-700">LAX</div>
                        <div class="mt-2 text-xs tracking-wide text-neutral-400">Los Angeles</div>
                      </div>
                    </div>
                    <div class="flex gap-0 justify-between mt-8 text-xs tracking-wide text-neutral-400">
                      <div class="capitalize">Departs on: 1 May, 08:00 AM</div>
                      <div class="text-right">
                        <span class="font-bold">4 days</span> to go
                      </div>
                    </div>
                  </div>
                </div>
                <div class="flex flex-col ml-5 w-[73%] max-md:ml-0 max-md:w-full">
                  <div class="flex flex-col max-md:mt-10 max-md:max-w-full">
                    <h3 class="text-sm tracking-wide uppercase text-stone-300 max-md:max-w-full">Prepare for your trip</h3>
                    <div class="flex gap-5 justify-between mt-4 text-xs tracking-wide whitespace-nowrap text-neutral-400 max-md:flex-wrap max-md:max-w-full">
                      <div class="flex flex-col justify-center">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/29c5bccc2a9d809c62faeb0dd39a7cea6a1ea7362359b4eaa64fff0e06bccf81?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Hotel Icon" class="self-center aspect-square w-[49px]" />
                        <div class="mt-1.5">Hotel</div>
                      </div>
                      <div class="flex flex-col justify-center text-center">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/4fcbbd1a670281bd8308374881c1aaee19e51df0c311629a8d8092a4f5b7d846?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Attractions Icon" class="self-center aspect-[1.22] w-[60px]" />
                        <div class="mt-1.5">Attractions</div>
                      </div>
                      <div class="flex flex-col justify-center text-center">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/63a08096fa9584222da683ce34785a29b306f895f1248ba8c14c084dd1820dc5?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Eats Icon" class="self-center w-12 aspect-[0.98]" />
                        <div class="mt-1.5">Eats</div>
                      </div>
                      <div class="flex flex-col justify-center text-center">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/43db7faa6fff57d45d69ba647c832b5c569a7ea09b6e27061410faf89b1b45b2?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Commute Icon" class="self-center aspect-[1.09] w-[53px]" />
                        <div class="mt-1.5">Commute</div>
                      </div>
                      <div class="flex flex-col justify-center text-center">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/224a43dd6bb0a53be8acf109621eba4fc1a8294ea1af84a0e40350e96c1ab970?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Taxi Icon" class="self-center aspect-[1.06] w-[52px]" />
                        <div class="mt-1.5">Taxi</div>
                      </div>
                      <div class="flex flex-col justify-center text-center">
                        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/183196c7c0b9457238db90194b8d0c0e89ca8fca8f4da8ed0c1c54081bfc71de?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Movies Icon" class="self-center aspect-square w-[49px]" />
                        <div class="mt-1.5">Movies</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
          <section class="flex gap-0 mt-16 max-md:flex-wrap max-md:mt-10">
            <div class="flex flex-col flex-1 font-bold max-md:max-w-full">
              <h2 class="text-sm tracking-wide text-sky-700 uppercase max-md:max-w-full">Plan your next trip</h2>
              <h3 class="mt-1 text-2xl tracking-wider capitalize text-zinc-800 max-md:max-w-full">Most Popular Destinations</h3>
            </div>
            <div class="flex gap-2 justify-between my-auto text-sm font-medium tracking-wide text-right text-sky-700 bg-white rounded-3xl">
              <a href="#">View all destinations</a>
              <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/995eb85743cf09973635d09cef72011dc83a9f7d24af47075f3c610ff22c2cef?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Arrow Icon" class="shrink-0 aspect-square w-[18px]" />
            </div>
          </section>
        </div>
        <aside class="flex flex-col ml-5 w-[26%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col mt-96 max-md:mt-10">
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/28fca2f380a4fc761825581e9b6494ecabc204c6ba0e5de38f5bfe4639ad187e?apiKey=842d01396d5643f1b863ca34dc4b2f79&" alt="Travel Website Logo" class="self-center aspect-[5.56] w-[373px]" />
            <h2 class="mt-80 text-4xl font-medium text-white max-md:mt-10">Travel Website</h2>
            <p class="mt-5 text-xl text-blue-300">Made by Team Locofy</p>
          </div>
        </aside>
      </div>
    </div>
  </div>
</template>