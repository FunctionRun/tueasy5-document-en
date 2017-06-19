# 图片\_Picture ![](/assets/Picture-icon.png)

---

## Code Model

### API
```
{
    'type': 'Image',
    'selected': false,
    'normal': {
        'src': '/public/images/default.png',
        'text': '',
        'imageStyle': {
            'borderRadius': '1px',
            'opacity': '1'
        },
        'textStyle': {
            'color': '#ccc',
            'fontSize': '14px',
            'marginLeft': 0,
            'marginTop': 0
        }
    },
    'mouse': {
        'src': '/public/images/default.png',
        'text': '',
        'imageStyle': {
            'borderRadius': '1px',
            'opacity': '1'
        },
        'textStyle': {
            'color': '#ccc',
            'fontSize': '14px',
            'marginLeft': 0,
            'marginTop': 0
        }
    },
    'emphasis': {
        'src': '/public/images/default.png',
        'text': '',
        'imageStyle': {
            'borderRadius': '1px',
            'opacity': '1'
        },
        'textStyle': {
            'color': '#ccc',
            'fontSize': '14px'
        }
    }
}
```

### Description

<table border="1">
    <tr>
       <th width="30%">Property</th>
   		<th width="30%">Description</th>
   		<th> value </th>
    </tr>
    <tr>
        <td>type | String </td>
        <td> 	Component type,unchangeable </td>
        <td>Image </td>
    </tr>
    <tr>
        <td>selected | Bool </td>
        <td> Whethe the picture is selected </td>
        <td> false </td>
    </tr>
    <tr>
        <td>normal | Object </td>
        <td>Style of the unselected state</td>
        <td> </td>
    </tr>
    <tr>
        <td>normal.src | String </td>
        <td>Url of the unselected picture </td>
        <td> </td>
    </tr>
    <tr>
        <td>normal.text | String </td>
        <td>Text of the unselected state </td>
        <td> </td>
    <tr>
        <td>normal.imageStyle | Object </td>
        <td>	Style of the unselected picture </td>
        <td><pre>
{
    'borderRadius': '1px',
    'opacity': '1'
}
        </pre></td>
    </tr>
    <tr>
        <td>normal.textStyle | Object</td>
        <td> Style of the unselected text
</td>
        <td><pre>
{
    'color': '#ccc',
    'fontSize': '14px',
    'marginLeft': 0,
    'marginTop': 0
}
        </pre></td>
    </tr>
    <tr>
        <td> mouse | Object  </td>
        <td>Style of the hovered picture by mouse </td>
        <td> </td>
    </tr>
    <tr>
        <td> mouse.src | String </td>
        <td>Url of the hovered picture </td>
        <td> </td>
    </tr>
    <tr>
        <td> mouse.text | String </td>
        <td>	Content when the picture is hovered</td>
        <td> </td>
    <tr>
        <td> mouse.imageStyle | Object </td>
        <td>Style of the hovered picture</td>
        <td><pre>
{
    'borderRadius': '1px',
    'opacity': '1'
}
        </pre></td>
    </tr>
    <tr>
        <td> mouse.textStyle </td>
        <td> Text style of the </td>
        <td><pre>
{
    'color': '#ccc',
    'fontSize': '14px',
    'marginLeft': 0,
    'marginTop': 0
}
        </pre></td>
    </tr>
    <tr>
        <td>emphasis | Object </td>
        <td>	Style of the hovered text </td>
        <td> </td>
    </tr>
    <tr>
        <td>emphasis.src | String </td>
        <td>Url of the selected picture </td>
        <td> </td>
    </tr>
    <tr>
        <td>emphasis.text | String </td>
        <td>	Content when the picture is selected</td>
        <td> </td>
    </tr>
    <tr>
        <td>emphasis.imageStyle | Object </td>
        <td>Style of the selected picture</td>
        <td><pre>
{
    'borderRadius': '1px',
    'opacity': '1'
}
        </pre></td>
    </tr>
    <tr>
        <td>emphasis.textStyle</td>
        <td>TextStyle of the selected text </td>
        <td><pre>
{
    'color': '#ccc',
    'fontSize': '14px'
}
        </pre></td>
    </tr>
</table>




