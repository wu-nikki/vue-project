<template lang="pug">
#home
  img(:src="prin")
  br
  br
  p
    | 嗨！歡迎加入國立科技高中。
    br
    | 參加社團不僅可以豐富自己的人生、寬闊自己的視野，
    br
    | 也能砥礪技能、磨練人際、培養第二專長。
    br
    | 選擇一項您喜歡的社團，積極的參與和投入，
    br
    | 您會獲得一陣陣的驚喜！
</template>

<script setup>
// 如果圖片 src 是綁定本機圖片，不能直接寫路徑
// const prin = '@/assets/0104.jpg'

const prin = new URL('@/assets/0104.jpg', import.meta.url).href
</script>
