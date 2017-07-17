# UserDefined ![](/assets/UserDefined.png)

---



## User Configuration

## ![](/assets/controls/UserDefined01.png)

Enter the code editor, using the VUE. Js, edit store to return to the main page after click the button to check), returned directly click the x button

## ![](/assets/controls/UserDefined02.png)

## Code Model



### API

```
{
    'type': 'UserDefined',
    'content': '<style> @@TE@@    div#UserDefiedapp {  @@TE@@    background-color: green;  @@TE@@    width: 300px;  @@TE@@    height: 50px; @@TE@@    line-height: 50px;  @@TE@@    } @@TE@@</style> @@TE@@<template>  @@TE@@    <div id="UserDefiedapp">{{message}}</div> @@TE@@</template>@@TE@@<script>    @@TE@@    new Vue({@@TE@@        el: "#UserDefiedapp",@@TE@@        data: {@@TE@@                message: "Hello Vue.js! You can use Vue in this control"@@TE@@            }@@TE@@        }) @@TE@@</script>',
    'series': [
        {
            'name': '群众求助',
            'value': 651
        },
        {
            'name': '交通类',
            'value': 594
        },
        {
            'name': '纠纷类',
            'value': 378
        },
        {
            'name': '违法类',
            'value': 219
        },
        {
            'name': '求助类',
            'value': 133
        }
    ]
}
```

### Description

<table border="1">
<tr>
	<th width="15%"> Property </th>
    <th width="50%"> Description </th>
   <th> Value </th>
</tr>
<tr>
	<td>type | String</td>
	<td>Type of Component</td>
	<td>UserDefined</td>
</tr>
<tr>
	<td>content | String</td>
	<td>Code content</td>
	<td></td>
</tr>
<tr>
	<td>series | Array[Object]</td>
	<td>Data series</td>
	<td></td>
</tr>
<tr>
	<td>series[0].name | String</td>
	<td>Text of Data</td>
	<td></td>
</tr>
<tr>
	<td>series[0].value | Array[Object]</td>
	<td>Key of Data</td>
	<td></td>
</tr>
</table>



