<template>
<div>

    <table>
        <thead>
            <th v-for='(item,i) in value.tableData[0]'>{{i}}</th>
        </thead>
        <tbody>
            <tr v-for='(item,i) in value.tableData' >
                <td v-for='(i2,i3) in item'>{{i2}}</td>
            </tr>
        </tbody>
    </table>  
</div>   
</template>
<script>
export default {
    props:['value'],
    data() {
        return {
            
        }
    },
    methods: {
        
        },
    
}
</script>

<style>

</style>