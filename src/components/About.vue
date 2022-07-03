<script setup>
import {ArrowRightIcon} from "@heroicons/vue/outline";

const skills = [
	{
		title: '成長迅速',
		description: '短短一年歲月，讓一隻原本600克的年輕小貓變成6公斤的肥宅，獲得獸醫應減肥認證。',
	},
	{
		title: '樸實無華',
		description: '最愛的逗貓棒是什麼都不掛的線，再美麗的羽毛或蝴蝶都吸引不了她的目光。',
	},
	{
		title: '不壞不愛',
		description: '撒嬌的首選對象永遠是平時對她最壞的爸爸：）。',
	},
	{
		title: '花瓶',
		description: '拍不死蟑螂，抓不到蚊子，要你何用？',
	},
	{
		title: '香',
		description: '聞過都說讚，就沒洗澡也讓人大呼過癮。',
	},
]
</script>

<template>

	<section id="about" class="pt-32 md:px-16 bg-amber-100">
		<div class="flex flex-col md:flex-row justify-around items-left md:px-8 md:mb-8">
			<h1 class="text-2xl md:text-4xl text-stone-800 font-bold">
				關於我
			</h1>
			<button
				class="my-8 ml-7 mr-7 border-b border-neutral-400 pb-2 flex items-left text-l text-neutral-400">
				 身為貓一定要怪ㄅ
				<ArrowRightIcon class="ml-1 w-5 h-5"/>
			</button>
		</div>
		<div class="flex flex-wrap justify-start">
			<div
				class="w-full md:w-1/3 mb-10"
				v-for="skill in skills">
				>
				<div
					class="px-10 sm:px-20 py-3 sm:py-6 shadow-lg w-11/12 mx-auto bg-white rounded z-20 relative">
					<h4 class="text-gray-800 text-lg text-center mb-2">{{ skill.title }}</h4>
					<p class="text-gray-600 text-lg text-center mb-2">{{ skill.description }}</p>
				</div>
			</div>
		</div>
	</section>
</template>