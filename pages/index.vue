<template>
    <div :class="$style.index">
        <UContainer>
            <div>Hello, World</div>
        </UContainer>
    </div>
</template>

<script setup lang="ts"></script>

<style lang="scss" module>
.index {
    width: 100%;
    height: 100%;

    box-sizing: border-box; // 전역 CSS로 옮겨야함
}
</style>
