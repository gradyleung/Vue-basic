<template>
    <div id="secondcomponent">
        <label><input type="radio" value="123" name="fruit">fruit</label>
        <select name="Name" id="select">
            <option value="Rose">Rose</option>
            <option value="Wade">Wade</option>
            <option value="James">James</option>
            <option value="T-Mac">T-Mac</option>
            <option value="Kobe2">Kobe2</option>
        </select>
        <h1>secondtest</h1>
        <h3>{{name}}</h3>
    </div>
</template>

<script type="text/javascript">
export default {
    data(){
        return{
            name:"grady"
        }
    }
}
</script>

<style>
    

</style>



