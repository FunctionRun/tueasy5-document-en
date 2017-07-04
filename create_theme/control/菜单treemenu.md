# 菜单\_TreeMenu ![](/assets/TreeMenu.png)

---
![](/assets/controls/TreeMenu01.png)


![](/assets/controls/TreeMenu03.png)

![](/assets/controls/TreeMenu04.png)

![](/assets/controls/TreeMenu05.png)

![](/assets/controls/TreeMenu06.png)

## Code Model

![](/assets/controls/TreeMenu02.png)

### API

```
{
    'type': 'treeMenu',
    'series': [
        {
            'name': '北京市',
            'value': 'beijing',
            'childrens': [
                {
                    'name': '朝阳区',
                    'value': 'chaoyangqu',
                    'childrens': [
                        {
                            'name': '朝阳公园',
                            'value': 'chaoyang park'
                        },
                        {
                            'name': '三里屯',
                            'value': 'sanlitun'
                        }
                    ]
                },
                {
                    'name': '海淀区',
                    'value': 'haidianqu'
                }
            ]
        },
        {
            'name': '上海市',
            'value': 'shanghai',
            'childrens': [
                {
                    'name': '徐汇区',
                    'value': 'xuhuiqu'
                },
                {
                    'name': '松江区',
                    'value': 'songjiangqu'
                },
                {
                    'name': '嘉定区',
                    'value': 'jiadingqu'
                }
            ]
        },
        {
            'name': '重庆市',
            'value': 'chongqing',
            'childrens': [
                {
                    'name': '渝北区',
                    'value': 'yubeiqu'
                },
                {
                    'name': '渝中区',
                    'value': 'yuzhongqu'
                },
                {
                    'name': '北碚区',
                    'value': 'beibeiqu'
                }
            ]
        }
    ],
    'titleName': '北京市',
    'SubTreeGap': 30,
    'itemStyle': {
        'primaryStyle': {
            'height': '40px',
            'fontFamily': '微软雅黑',
            'fontSize': '14px',
            'color': '#fff',
            'display': 'inline-block',
            'backgroundColor': 'rgb(102, 118, 136)',
            'lineHeight': '40px'
        },
        'primaryArrowStyle': {
            'fontSize': '18px',
            'color': 'rgb(255, 255, 255)'
        },
        'menuStyle': {
            'normal': {
                'fontSize': '14px',
                'color': '#fff',
                'backgroundColor': 'rgb(102, 118, 136)',
                'fontFamily': '微软雅黑',
                'lineHeight': '30px'
            },
            'emphasis': {
                'color': '#1C243B',
                'backgroundColor': 'rgb(239, 241, 243)'
            }
        }
    }
}
```

### Description

<table border="1">
    <tr>
        <th width="15%"> Property </th>
		<th width="30%">Description</th>
		<th> Value </th>
    </tr>
    <tr>
        <td> type | String</td>
        <td>Component type, unchangeable </td>
        <td>treeMenu</td>
    </tr>
    <tr>
        <td> series | Array(Object)</td>
        <td>Data option of the tree menu, every object item of the array means a level one item</td>
        <td> </td>
    </tr>
    <tr>
        <td> series[0].name | String</td>
        <td>Text of the menu item, repeated </td>
        <td> </td>
    </tr>
    <tr>
        <td> series[0].value | String</td>
        <td>	Uniquely identification of a menu item </td>
        <td> </td>
    </tr>
    <tr>
        <td> series[0].children | Object</td>
        <td>Child item of this menu item with same constructure </td>
        <td> </td>
    </tr>
    <tr>
        <td> titleName | String </td>
        <td>Default text of the menu items, only show when any item is not selected</td>
        <td> </td>
    </tr>
    <tr>
        <td> SubTreeGap | String </td>
        <td>Right indent between child menu and father menu </td>
        <td>30px</td>
    </tr>
    <tr>
        <td> itemStyle | Object </td>
        <td>Style of menu item </td>
        <td> </td>
    </tr>
    <tr>
        <td> itemStyle.primaryStyle | Object </td>
        <td>Primary style of menu item</td>
        <td><pre>
{
    'height': '40px',
    'fontFamily': '微软雅黑',
    'fontSize': '14px',
    'color': '#fff',
    'display': 'inline-block',
    'backgroundColor': 'rgb(102, 118, 136)',
    'lineHeight': '40px' 
}
    </pre></td>
    </tr>
    <tr>
        <td> itemStyle.primaryArrowStyle| Object </td>
        <td>Primary style of menu item </td>
        <td><pre>
{
    'fontSize': '18px',
    'color': 'rgb(255, 255, 255)'
}
        </pre></td>
    </tr>
    <tr>
        <td>itemStyle.menuStyle | Object </td>
        <td>	Dropdown style of menu item </td>
        <td> </td>
    </tr>
    <tr>
        <td>itemStyle.menuStyle.normal | Object  </td>
        <td>Unselected style of dropdown menu </td>
        <td><pre>
{
    'fontSize': '14px',
    'color': '#fff',
    'backgroundColor': 'rgb(102, 118, 136)',
    'fontFamily': '微软雅黑',
    'lineHeight': '30px'
}
        </pre></td>
    </tr>
    <tr>
        <td>itemStyle.menuStyle.emphasis | Object  </td>
        <td>	Selected style of dropdown menu </td>
        <td><pre>
{
    'color': '#1C243B',
    'backgroundColor': 'rgb(239, 241, 243)'
}
        </pre></td>
    </tr>
</table>




