<template>
  <header class="flex flex-col gap-y-6 w-full mb-[2vh] lg:mt-[1vh]">
    <section
      class="flex w-full flex-col gap-y-2 items-center text-center max-w-[37.5rem] mx-auto"
    >
      <div class="relative">
        <h1
          class="font-display text-3xl font-semibold tracking-tight text-pretty md:text-4xl"
        >
          Discover Events and Gatherings Near You
        </h1>
        <div
          class="absolute -bottom-2 inset-x-0 h-8 bg-gradient-to-t from-background/40 to-transparent pointer-events-none select-none"
        />
      </div>
      <div
        class="prose prose-neutral dark:prose-invert prose-a:font-normal prose-a:text-foreground hover:prose-a:text-primary first:prose-p:mt-0 last:prose-p:mb-0 first:prose-ul:mt-0 last:prose-ul:mb-0 prose-li:mt-2 first:prose-li:m-0 prose-img:border prose-img:border-neutral-200 prose-img:rounded-md prose-lead:text-lg/relaxed prose-pre:font-mono prose-pre:rounded-none text-secondary text-pretty leading-relaxed prose-headings:scroll-mt-20 prose-headings:text-foreground prose-headings:font-semibold prose-headings:tracking-tight prose-h1:text-3xl md:prose-h1:text-4xl prose-h2:text-2xl md:prose-h2:text-3xl prose-h3:text-2xl prose-h4:text-xl prose-h5:text-base prose-h5:font-medium prose-h5:tracking-micro prose-h6:text-sm prose-h6:font-medium prose-h6:tracking-normal max-w-2xl"
      >
        <h2
          class="!text-base !font-normal !tracking-normal !text-foreground/70 md:!text-lg"
        >
          A curated list of the best gatherings, meetups, and conferences, all
          in one place. Register, get your QR code, and be part of the
          experience.
        </h2>
      </div>
    </section>
    <section
      class="flex gap-x-4 gap-y-3 flex-col min-w-0 max-w-xs md:max-w-md w-full mx-auto items-center text-center"
    >
      <form
        class="flex border rounded-lg overflow-clip focus-within:outline focus-within:outline-2 focus-within:-outline-offset-1 focus-within:outline-primary w-full"
      >
        <input
          class="w-full appearance-none bg-background text-foreground resize-none font-medium outline-offset-0 outline-primary placeholder:text-inherit placeholder:opacity-50 disabled:opacity-50 px-4 py-2.5 text-sm/tight rounded-lg flex-1 min-w-0 border-0 outline-0"
          type="text"
          name="search"
          placeholder="Type to search"
          data-1p-ignore="true"
          required
        />
        <Button class="m-1 px-4 py-1.5">Seach your event</Button>
      </form>
    </section>
  </header>
</template>
