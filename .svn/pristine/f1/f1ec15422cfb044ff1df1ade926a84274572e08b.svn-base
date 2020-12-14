/*购物车JS*/
$(function(){
    //1.全选
    //点击表头的全选框，获取表头全选框的状态
    //表格中的单选框需要一致
    //结算中的全选状态一致
    $('table thead input[type=checkbox]').change(function(){
        //获取选中状态
        var state = $(this).prop('checked');
        //让表格中的单选框保持一致 ,结算中的选择框状态保持一致
        $('table tbody input[type=checkbox], .totalPrice input[type=checkbox]').prop('checked', state);
        
    })
    //2.结算中的选择框也需要有相同的功能
    $('.totalPrice input[type=checkbox]').change(function(){
        var state = $(this).prop('checkde');
        //上面的全选和表格中的input状态一致
        $('table tbody input[type=checkbox], .table thead input [type=checkbox]').prop('checked',state);
    })
})
