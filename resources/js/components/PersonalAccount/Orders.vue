<template>
    <div class="personal-account__content">
        <h3 class="personal-account__title personal-account__title_black">
            Мои заказы {{OrdersCompleted}}
        </h3>
        <div class="personal-account-orders">
            <div class="personal-account-orders__links">
                <div class="personal-account-orders__link"
                     :class="{ 'personal-account-orders__link_active': OrdersCompleted === false }"
                     @click="OrdersUpcomingToggle()"
                >
                    Предстоящие
                </div>
                <div class="personal-account-orders__link"
                     :class="{ 'personal-account-orders__link_active': OrdersCompleted === true }"
                     @click="OrdersCompletedToggle()"
                >
                    Завершенные
                </div>
            </div>
            <OrdersUpcoming v-if="OrdersCompleted === false"></OrdersUpcoming>
            <OrdersCompleted v-if="OrdersCompleted === true"></OrdersCompleted>
        </div>
    </div>
</template>

<script>

import OrdersCompleted from "./OrdersCompleted";
import OrdersUpcoming from "./OrdersUpcoming";

export default {
    name: "Orders",
    components: {
        OrdersCompleted,
        OrdersUpcoming,
    },
    data: () => ({
        OrdersCompleted: true,
    }),
    methods: {
        OrdersUpcomingToggle() {
            this.OrdersCompleted = false;
        },
        OrdersCompletedToggle() {
            this.OrdersCompleted = true;
        },
    }
}
</script>

<style scoped>

</style>
