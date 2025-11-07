<script setup>
import { Icon } from '@iconify/vue'
</script>

<template>
  <Column class="max-w-4xl mx-auto px-4 py-8">
    <div class="text-center mb-12">
      <h1 class="text-4xl font-bold mb-4">社交媒体</h1>
      <p class="text-gray-600 text-lg">在这里找到我的各个社交平台账号</p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
      <div class="bg-white p-6 rounded-lg border border-gray-200 hover:shadow-lg transition-shadow">
        <div class="flex items-center mb-4">
          <Icon icon="ri:weibo-fill" class="text-2xl text-red-500 mr-3" />
          <h2 class="text-xl font-semibold">微博</h2>
        </div>
        <p class="text-gray-600 mb-4">分享日常生活和有趣的内容</p>
        <a
          href="https://weibo.com"
          target="_blank"
          rel="noopener noreferrer"
          class="text-blue-600 hover:underline"
        >
          访问微博 →
        </a>
      </div>

      <div class="bg-white p-6 rounded-lg border border-gray-200 hover:shadow-lg transition-shadow">
        <div class="flex items-center mb-4">
          <Icon icon="ri:github-fill" class="text-2xl text-gray-800 mr-3" />
          <h2 class="text-xl font-semibold">GitHub</h2>
        </div>
        <p class="text-gray-600 mb-4">开源项目和技术分享</p>
        <a
          href="https://github.com"
          target="_blank"
          rel="noopener noreferrer"
          class="text-blue-600 hover:underline"
        >
          访问 GitHub →
        </a>
      </div>

      <div class="bg-white p-6 rounded-lg border border-gray-200 hover:shadow-lg transition-shadow">
        <div class="flex items-center mb-4">
          <Icon icon="ri:zhihu-fill" class="text-2xl text-blue-600 mr-3" />
          <h2 class="text-xl font-semibold">知乎</h2>
        </div>
        <p class="text-gray-600 mb-4">技术问答和深度文章</p>
        <a
          href="https://zhihu.com"
          target="_blank"
          rel="noopener noreferrer"
          class="text-blue-600 hover:underline"
        >
          访问知乎 →
        </a>
      </div>

      <div class="bg-white p-6 rounded-lg border border-gray-200 hover:shadow-lg transition-shadow">
        <div class="flex items-center mb-4">
          <Icon icon="ri:wechat-fill" class="text-2xl text-green-600 mr-3" />
          <h2 class="text-xl font-semibold">微信公众号</h2>
        </div>
        <p class="text-gray-600 mb-4">原创文章和学习笔记</p>
        <a href="#" class="text-blue-600 hover:underline"> 查看公众号 → </a>
      </div>
    </div>
  </Column>
</template>
