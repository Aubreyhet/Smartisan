<template>
    <div>
        <h1>情人节快乐</h1>
        <ul>
            <li v-for="item in shopsData" :key="item.id">
                {{item.name}} 价格 {{item.price}}
            </li>
        </ul>
    </div>
</template>

<script>
import shopsData from '../lib/shopSku.js'
export default {
    data () {
        return {
            shopsData//: [{
//     //id
//     "id": 1052001,
//     //商品名称
//     "name": "情人节玫瑰花99朵",
//     //商品描述
//     "name_title": "99表示久久，相爱的两个人永远在一起",
//     "price": 49,
//     //商品详情描述
//     "sku_info":[{
//         "sku_id":105200101,
//         "title": "巴拉巴拉",
//         "sub_title": "巴拉巴拉",
//         "price": 49,
//         "limit_num": 5,
//     },{
//         "sku_id":105200102,
//         "title": "巴拉巴拉",
//         "sub_title": "巴拉巴拉",
//         "price": 9,
//         "limit_num": 5,
//     },{
//         "sku_id":105200103,
//         "title": "巴拉巴拉",
//         "sub_title": "巴拉巴拉",
//         "price": 49,
//         "limit_num": 5,
//     }]
    
// },{
//         //id
//         "id": 1052002,
//         //商品名称
//         "name": "情人节玫瑰花99朵",
//         //商品描述
//         "name_title": "99表示久久，相爱的两个人永远在一起",
//         "price": 9,
//         //商品详情描述
//         "sku_info":[{
//             "sku_id": 105200201,
//             "title": "巴拉巴拉",
//             "sub_title": "巴拉巴拉",
//             "price": 49,
//             "limit_num": 5,
//         },{
//             "sku_id": 105200202,
//             "title": "巴拉巴拉",
//             "sub_title": "巴拉巴拉",
//             "price": 49,
//             "limit_num": 5,
//         },{
//             "sku_id": 105200203,
//             "title": "巴拉巴拉",
//             "sub_title": "巴拉巴拉",
//             "price": 49,
//             "limit_num": 5,
//         }]
        
// }]
        }
    }
}
</script>

<style>
h1{
    color: tomato;
}
ul li{
    list-style: none;
    float: left;
    margin-right: 30px;
}
</style>

