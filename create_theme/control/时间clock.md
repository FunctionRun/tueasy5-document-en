# 时间\_Clock ![](/assets/Clock.png)

---

## Code Model

### API

```
{
    'time': {
        'secondShow': false,
        'normal': {
            'color': '#616a73',
            'fontSize': '50px',
            'line-height': '30px',
            'position': 'absolute',
            'left': 55,
            'top': 16
        }
    },
    'date': {
        'normal': {
            'color': '#84b0ed',
            'fontSize': '18px',
            'position': 'absolute',
            'left': 19,
            'top': 70
        }
    },
    'week': {
        'normal': {
            'color': '#84b0ed',
            'fontSize': '18px',
            'position': 'absolute',
            'right': 21,
            'top': 70
        }
    },
    'border': {
        'show': true,
        'normal': {
            'borderColor': '#85bbbd'
        }
    }
}
```

### Description


<table border="1">
    <tr>
        <th width="15%"> Property </th>
        <th width="30%"> Description </th>
        <th> Value </th>
    </tr>
    <tr>
        <td>time | Object  </td>
        <td> Time Config </td>
        <td> </td>
    </tr>
    <tr>
        <td>time.secondShow | Bool </td>
        <td> Whether show second </td>
        <td>false</td>
    </tr>
    <tr>
        <td>time.normal | Object </td>
        <td> Time Styles</td>
        <td><pre>
{
    'color': '#616a73',
    'fontSize': '50px',
    'line-height': '30px',
    'position': 'absolute',
    'left': 55,
    'top': 16
}
        </pre></td>
    </tr>
    <tr>
        <td>date | Object </td>
        <td> Date Config </td>
        <td> </td>
    </tr>
    <tr>
        <td>date.normal | Object </td>
        <td> Date style </td>
        <td><pre>
{
    'color': '#84b0ed',
    'fontSize': '18px',
    'position': 'absolute',
    'left': 19,
    'top': 70
}
        </pre></td>
    </tr>
    <tr>
        <td>week | Object </td>
        <td>Week Config </td>
        <td> </td>
    </tr>
    <tr>
        <td>week.normal | Object </td>
        <td>Week style</td>
        <td><pre>
{
    'color': '#84b0ed',
    'fontSize': '18px',
    'position': 'absolute',
    'right': 21,
    'top': 70
}
        </pre></td>
    </tr>
    <tr>
        <td>border | Object </td>
        <td>Border config</td>
        <td> </td>
    </tr>
    <tr>
        <td>border.show | Bool </td>
        <td> Whether show border </td>
        <td>false</td>
    </tr>
    <tr>
        <td>border.normal | Object </td>
        <td>Border style, when and only when the border. The show has a value of true and effective</td>
        <td><pre>
{
    'borderColor': '#85bbbd'
}
        </pre></td>
    </tr>
</table>




