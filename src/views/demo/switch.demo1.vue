<template>
    <div>
        <s-switch v-model="value"></s-switch>
    </div>
</template>

<script>
import SSwitch from "@lib/switch/switch"
export default {
    components: {
        SSwitch
    },
    data() {
        return {
            value: true
        }
    }
}
</script>