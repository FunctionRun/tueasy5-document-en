# 时间\_MultiCalendar ![](/assets/MultiCalendar.png)

---

## Code Model

### API

```
{
    'type': 'multiCalendar',
    'themeColor': '#667688',
    'orient': 'vertical',
    'inputStyle': {
        'color': '#333',
        'fontSize': '20px',
        'fontFamily': 'simsun'
    },
    'buttonStyle': {
        'normal': {
            'backgroundColor': '#33b26e',
            'color': 'white',
            'fontSize': '18px',
            'width': '100px'
        },
        'emphsis': {
            'backgroundColor': 'violet',
            'color': 'cyan',
            'fontSize': '18px'
        }
    }
}
```

### Description

<table border="1">
    <tr>
        <th width="15%"> Property </th>
        <th width="30%">Description</th>
        <th>Value</th>
    </tr>
    <tr>
        <td> type | String </td>
        <td>Type of Component </td>
        <td>multiCalendar </td>
    </tr>
    <tr>
        <td> themeColor | String </td>
        <td>Theme color  </td>
        <td> \#667688 ('Color Name'、HEX、RGB、RGBA、HSL、HSLA、transparent ) </td>
    </tr>
    <tr>
        <td> orient | String </td>
        <td> Layout has two choice horizontal and vertical </td>
        <td>vertical (horizontal、vertical) </td>
    </tr>
    <tr>
        <td> inputStyle | Object </td>
        <td> Input style  </td>
        <td><pre>
{
    'color': '#333',
    'fontSize': '20px',
    'fontFamily': 'simsun'
}
        </pre></td>
    </tr>
    <tr>
        <td>buttonStyle | Object </td>
        <td> Button of OK style  </td>
        <td> </td>
    </tr>
    <tr>
        <td>buttonStyle.normal | Object </td>
        <td> Button of OK style  </td>
        <td><pre>
{
    'backgroundColor': '#33b26e',
    'color': 'white',
    'fontSize': '18px',
    'width': '100px'
}
        </pre></td>
    </tr>
    <tr>
        <td> buttonStyle.emphsis </td>
        <td> Button of OK style when mouseover </td>
        <td><pre>
{
    'backgroundColor': 'violet',
    'color': 'cyan',
    'fontSize': '18px'
}
        </pre></td>
    </tr>
</table>




