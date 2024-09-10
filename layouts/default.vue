<template>
    <v-app>
        <div :class="$style.index">
            <slot />
        </div>
    </v-app>
</template>

<style lang="scss" module>
.index {
    width: 100%;
    height: 100%;
}
</style>
