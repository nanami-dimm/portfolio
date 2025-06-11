<template>
  <div class="p-8">
    <h2 class="text-2xl font-semibold mb-4">お問い合わせ</h2>
    <form class="space-y-4">
      <input type="text" placeholder="お名前" class="border p-2 w-full" />
      <input
        type="email"
        placeholder="メールアドレス"
        class="border p-2 w-full"
      />
      <textarea
        placeholder="お問い合わせ内容"
        class="border p-2 w-full"
        rows="5"
      />
      <button type="submit" class="bg-blue-500 text-white px-4 py-2 rounded">
        送信
      </button>
    </form>
  </div>
</template>
