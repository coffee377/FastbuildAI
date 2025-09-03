<script setup>
const router = useRouter();
const { t } = useI18n();
</script>
<template>
    <div class="knowledge-container flex h-full flex-col">
        <!--        <UButton-->
        <!--            class="absolute top-1/2 -translate-y-[50%]"-->
        <!--            variant="link"-->
        <!--            color="neutral"-->
        <!--            :label="$t('console-ai-datasets.dataset.title')"-->
        <!--            leading-icon="i-lucide-chevron-left"-->
        <!--            @click="-->
        <!--                router.replace(-->
        <!--                    !!props.id-->
        <!--                        ? useRoutePath('ai-datasets-documents:list', { id: props.id })-->
        <!--                        : useRoutePath('ai-datasets:list'),-->
        <!--                )-->
        <!--            "-->
        <!--        />-->
        创建知识库
    </div>
</template>
