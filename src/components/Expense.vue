<template>
    <div class="justify-content-center d-flex cold-12 align-center">
        <b-container class="bv-example-row ">
            <div class="d-flex gap-3 ">
                <b-form-input class=" col-6 mr-2" v-model="expenseValue" placeholder="Enter your number" type="number">
                </b-form-input>
                <b-button @click="addExpense" variant="primary">Add Expense</b-button>
            </div>
                <p>{{ExpenseResult}}</p>

        </b-container>
    </div>
</template>

<script>
export default {
    name: 'App',
    data() {
        return {
            expenseValue: '',
            ExpenseResult: '',
        }
    },
    methods: {
       addExpense() {
           this.ExpenseResult = this.expenseValue;
       }
    }

}
</script>

<style>
</style>