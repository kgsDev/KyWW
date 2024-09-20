<template>
	<PageContainer>
		<img class="w-48 ml-auto mr-0" src="~/assets/illustrations/tokyo-luminous-table-lamp-on-boxes.svg" />
		<TypographyHeadline :content="headContent" size="xl" />
		<VDivider class="my-8" />
		<textarea v-model="emailList" class="w-full" placeholder="Enter emails separated by , ; or space"></textarea>
		<UButton variant="solid" @click="submitEmails">Submit</UButton>
	</PageContainer>
</template>
<script setup>
const headContent = 'Trainer Email Registration';
</script>
