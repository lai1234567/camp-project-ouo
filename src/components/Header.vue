<script setup>
import { ArrowRightIcon, ChevronDoubleDownIcon} from '@heroicons/vue/solid'

</script>
<template>
	<section class="bg-yellow-50 flex flex-col justify-center items-center md:px-20 min-h-screen">
		<div class="flex flex-col w-full py-12 px-4 lg:px-10 justify-center items-start">
			<p class="text-2xl text-gray-800 font-medium">嗨大家 這裡介紹一隻<span class="text-yellow-500">可愛ㄉ卯咪</span></p>
			<h1 class="text-5xl text-left text-gray-800 mt-5 font-extrabold">
				喵
			</h1>
			<p class="text-lg text-gray-500 font-light pt-8">
				[名灰灰；今年一歲；性別女；擅長打翻飲料]
			</p>
			<a
				href="#contact"
				class="mt-3 flex items-center text-xl font-regular pb-2">
				向我表忠
        <ArrowRightIcon class="ml-1 w-5 h-5"/>
			</a>
		</div>

		<a href="#activities" class="animate-bounce cursor-pointer">
			<chevron-double-down-icon class="w-16 h-25"/>
		</a>
	</section>
</template>
