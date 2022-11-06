<template>
    <div class="personal-account__content">
        <h3 class="personal-account__title personal-account__title_black">
            Мои транзакции
        </h3>
        <div class="personal-account-transactions__row">
            <div class="personal-account-transactions-check dt-check personal-account-check">
                <div class="personal-account-transactions-check__input dt-check__input">
                    <input type="radio" name="transactions_status">
                    <div class="dt-check__input-check"></div>
                </div>
                <label class="personal-account-transactions-check__label dt-check__label">
                    <slot name="label">
                        <h5>
                            все
                        </h5>
                    </slot>
                </label>
            </div>
            <div class="personal-account-transactions-check dt-check personal-account-check">
                <div class="personal-account-transactions-check__input dt-check__input">
                    <input type="radio" name="transactions_status">
                    <div class="dt-check__input-check"></div>
                </div>
                <label class="personal-account-transactions-check__label dt-check__label">
                    <slot name="label">
                        <h5>
                            в ожидании
                        </h5>
                    </slot>
                </label>
            </div>
            <div class="personal-account-transactions-check dt-check personal-account-check">
                <div class="personal-account-transactions-check__input dt-check__input">
                    <input type="radio" name="transactions_status">
                    <div class="dt-check__input-check"></div>
                </div>
                <label class="personal-account-transactions-check__label dt-check__label">
                    <slot name="label">
                        <h5>
                            отклоненные
                        </h5>
                    </slot>
                </label>
            </div>
            <div class="personal-account-transactions-check dt-check personal-account-check">
                <div class="personal-account-transactions-check__input dt-check__input">
                    <input type="radio" name="transactions_status">
                    <div class="dt-check__input-check"></div>
                </div>
                <label class="personal-account-transactions-check__label dt-check__label">
                    <slot name="label">
                        <h5>
                            оплаченные
                        </h5>
                    </slot>
                </label>
            </div>
        </div>
        <div class="personal-account-transactions">
            <TransactionCard v-for="item in transactions_list" :key="item.id" :item="item"></TransactionCard>
        </div>
    </div>
</template>

<script>
import TransactionCard from "./TransactionCard";

export default {
    name: "Transactions",
    components: {
        TransactionCard
    },
    data: () => ({
        transactions_list: [
            {
                id: 3651490,
                amount: 3651490,
                name_tour: "Некоторое название экскурсии",
                status: "в ожидании",
            },
            {
                id: 3651490,
                amount: 3651490,
                name_tour: "Некоторое название экскурсии",
                status: "оплачено",
            },
            {
                id: 3651490,
                amount: 3651490,
                name_tour: "Некоторое название экскурсии",
                status: "отклонено",
            }
        ]
    })
}
</script>

<style scoped>

</style>
