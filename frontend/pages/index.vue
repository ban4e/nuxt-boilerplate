<template>
    <div class="grid-container mt-32">
        <div class="grid-list">
            <div class="grid-item grid-item_4x">
                Иконка
                <BaseIcon name="angle-down" :is-box="true" />
            </div>
            <div class="grid-item grid-item_4x">
                <BaseButton>
                    Кнопка
                    <template #suffix>
                        <BaseIcon name="angle-down" :is-box="true" />
                    </template>
                </BaseButton>
            </div>
            <div class="grid-item grid-item_4x">Сетка</div>
        </div>
    </div>
</template>

<script>
export default {};
</script>
