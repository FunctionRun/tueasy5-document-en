# 走马灯\_Marquee ![](/assets/Marquee.png)

---

![](/assets/controls/Marquee01.png)

## Code Model

![](/assets/controls/Marquee02.png)

### API

```
{
    'type': 'Marquee',
    'series': [
        {
            'date': '2016.9.2',
            'time': '12:28:39',
            'content': '渝北区邮政银行遭遇抢劫'
        },
        {
            'date': '2016.9.2',
            'time': '22:28:39',
            'content': '渝北区珠宝店有小偷进入'
        },
        {
            'date': '2016.9.2',
            'time': '23:28:39',
            'content': '人民大街发生车祸'
        },
        {
            'name': '车辆轨迹',
            'value': 'carInfo'
        },
        {
            'name': '人员密度',
            'value': 'personIdentity'
        },
        {
            'name': '路况',
            'value': 'roadInfo'
        }
    ],
    'categoryGap': '80px',
    'itemGap': '20px',
    'speedTime': 20,
    'speedDistance': '2px',
    'itemStyle': {
        'normal': {
            'fontSize': '20px',
            'color': '#c1c1c1',
            'background': '#eff1f3',
            'paddingLeft': '5px'
        }
    }
}
```

### Description

<table border="1" >
    <tr>
        <th width="15%"> Property </th>
        <th width="45%"> Description </th>
        <th> Value </th>
    </tr>
    <tr>
        <td>type | String</td>
        <td>Type of Component</td>
        <td>Marquee</td>
    </tr>
    <tr>
        <td>series | Array[Object]</td>
        <td>	Data of the component </td>
        <td> <pre>
            [
                {
                    'name': '人员密度',
                    'value': 'personIdentity', //Uniquely identification of data, unrepeatable
                }
            ]
        </pre> </td>
    </tr>
    <tr>
        <td>categoryGap | String </td>
        <td>Gap between the items </td>
        <td> 20px |  5% </td>
    </tr>
    <tr>
        <td>itemGap | Sting </td>
        <td>Gap between text in items </td>
        <td> 5px |  1% </td>
    </tr>
    <tr>
        <td>speedTime | Number </td>
        <td>Animate fresh time (unit is ms)</td>
        <td> 20 </td>
    </tr>
    <tr>
        <td>speedDistance | String </td>
        <td>Animation moved at a time  </td>
        <td> 2px </td>
    </tr>
    <tr>
        <td>itemStyle.normal | Object</td>
        <td>Item style </td>
        <td><pre>
            
            {
                'fontSize': '20px',  
                'color': '#c1c1c1',  
                'background': '#eff1f3',  
                'paddingLeft': '5px'  
            }

        </pre></td>
    </tr>

</table>

> Notes：
>
> Difference between  categoryGap and itemGap like this:

![](/assets/marquee01.png)

