<template>
  <main px-4 py-10 text="center gray-700 dark:gray-200">
    <RouterView />
    <TheFooter />
    <div mx-auto mt-5 text-center text-sm opacity-50>
      [Builder Layout]
    </div>
  </main>
</template>

<route lang="yaml">
  meta:
    layout: editor
</route>
