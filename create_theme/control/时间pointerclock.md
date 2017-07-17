# PionterClock ![](/assets/PointerClock.png)

---

![](/assets/controls/PointerClock01.png)

![](/assets/controls/PointerClock03.png)

![](/assets/controls/PointerClock04.png)


## Code Model

![](/assets/controls/PointerClock02.png)

### API

```
{
    'clock': {
        'clockAxis': {
            'axisLine': {
                'show': true,
                'lineStyle': {
                    'stroke': '#5a9cc7'
                }
            },
            'axisTick': {
                'show': true,
                'lineStyle': {
                    'stroke': '#5a9cc7'
                }
            },
            'axisText': {
                'textGap': 5,
                'textStyle': {
                    'stroke': '#5a9cc7'
                }
            }
        },
        'outerCircle': {
            'show': true,
            'lineStyle': {
                'fill': '#5a9cc7'
            }
        },
        'middleCircle': {
            'show': true,
            'lineStyle': {
                'stroke': '#5a9cc7'
            }
        },
        'innerCircle': {
            'show': true,
            'lineStyle': {
                'stroke': '#5a9cc7'
            }
        },
        'hand': {
            'clockHourHand': {
                'handStyle': {
                    'fill': '#5a9cc7',
                    'stroke': '#5a9cc7'
                },
                'lineStyle': {
                    'stroke': '#5a9cc7'
                }
            },
            'clockMinuteHand': {
                'handStyle': {
                    'fill': '#5a9cc7',
                    'stroke': '#5a9cc7'
                },
                'lineStyle': {
                    'fill': '#5a9cc7'
                }
            },
            'clockSecondHand': {
                'handStyle': {
                    'fill': '#5a9cc7'
                },
                'lineStyle': {
                    'fill': '#5a9cc7'
                }
            }
        },
        'aloneArc': {
            'show': true,
            'lineStyle': {
                'fill': '#5a9cc7',
                'stroke': '#5a9cc7'
            }
        },
        'symmetryArc': {
            'show': true,
            'lineStyle': {
                'fill': '#5a9cc7',
                'stroke': '#5a9cc7'
            }
        }

    },
    'series': [
        {
            'type': 'PointerClock'
        }
    ]
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
        <td> clock | Object  </td>
        <td>Style of clock </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.clockAxis | Object  </td>
        <td>Style of scale line </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisLine | Object </td>
        <td>Style of circle line</td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisLine.show | Bool  </td>
        <td>Whether or not to show circle line </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisLine.lineStyle | Object </td>
        <td>Style of circle line </td>
        <td><pre>
    {
        'stroke': '#5a9cc7'
    }
        </pre></td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisTick | Object  </td>
        <td>Style of scale line</td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisTick.show | Bool </td>
        <td>Whether or not to show the scale line </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisTick.lineStyle | Object </td>
        <td>The style of the scale line </td>
        <td><pre>
    {
        'stroke': '#5a9cc7'
    }
        </pre></td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisText | Object </td>
        <td>Style of number </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisText.textGap | String </td>
        <td>Gap between number and circle line </td>
        <td>'5px'</td>
    </tr>
    <tr>
        <td>clock.clockAxis.axisText.textStyle | Object </td>
        <td>Text style of number </td>
        <td><pre>
    {
        'stroke': '#5a9cc7'
    }
        </pre></td>
    </tr>
    <tr>
        <td>clock.outerCircle | Object  </td>
        <td>Style of outer circle</td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.outerCircle.show | Bool </td>
        <td>Whether or not to show the outer circle </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.outerCircle.lineStyle | Object </td>
        <td>	The style of the outer circle line </td>
        <td><pre>
    {
        'stroke': '#5a9cc7'
    }
        </pre></td>
    </tr>
    <tr>
        <td>clock.middleCircle | Object </td>
        <td>Style of middle circle </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.middleCircle.show | Bool </td>
        <td>Whether or not to show the middle circle </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.middleCircle.lineStyle | Object </td>
        <td>	The style of the middle circle line </td>
        <td><pre>
    {
        'stroke': '#5a9cc7'
    }
        </pre></td>
    </tr>
    <tr>
        <td>clock.innerCircle | Object </td>
        <td>Style of inner circle </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.innerCircle.show | Bool </td>
        <td>Whether or not to show inner circle </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.innerCircle.lineStyle | Object </td>
        <td>Style of inner circle line </td>
        <td><pre>
    {
        'stroke': '#5a9cc7'
    }
        </pre></td>
    </tr>
    <tr>
        <td>clock.hand | Object </td>
        <td>Style of hand </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.hand.clockHourHand | Object </td>
        <td>Color of hour hand</td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.hand.clockHourHand.handStyle | Object </td>
        <td>Style of hour handle </td>
        <td><pre>
{
    'fill': '#5a9cc7',
    'stroke': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td>clock.hand.clockHourHand.lineStyle | Object </td>
        <td>Color of the rest part of hour handle </td>
        <td><pre>
{
    'stroke': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td>clock.hand.clockMinuteHand | Object </td>
        <td>	Style of minute hand </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.hand.clockMinuteHand.handStyle | Object </td>
        <td>Style of minute handle </td>
        <td><pre>
{
    'fill': '#5a9cc7',
    'stroke': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td>clock.hand.clockMinuteHand.lineStyle | Object </td>
        <td>Color of the rest part of minute handle </td>
        <td><pre>
{
    'fill': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td>clock.hand.clockSecondHand | Object </td>
        <td>Style of second hand </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.hand.clockSecondHand.handStyle | Object </td>
        <td>Style of second handle </td>
        <td><pre>
{
    'fill': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td>clock.hand.clockSecondHand.lineStyle | Object </td>
        <td> Color of the rest part of second handle
 </td>
        <td><pre>
{
    'fill': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td> clock.aloneArc | Object </td>
        <td>Single arc to decorate the clock</td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.aloneArc.show | Bool </td>
        <td>	Whether or not to show the single arc </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.aloneArc.lineStyle | Object </td>
        <td>Style of the single arc </td>
        <td><pre>
{
    'fill': '#5a9cc7',
    'stroke': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td>clock.symmetryArc | Object </td>
        <td>Symmetrical arcs to decorate the clock </td>
        <td> </td>
    </tr>
    <tr>
        <td>clock.symmetryArc.show | Bool </td>
        <td>Whether or not to show the symmetrical arcs </td>
        <td>true</td>
    </tr>
    <tr>
        <td>clock.symmetryArc.lineStyle | Object </td>
        <td>Style of the symmetrical arcs </td>
        <td><pre>
{
    'fill': '#5a9cc7',
    'stroke': '#5a9cc7'
}
        </pre></td>
    </tr>
    <tr>
        <td> series | Array[Object]</td>
        <td> Data series</td>
        <td> </td>
    </tr>
    <tr>
        <td> series[0].type | String</td>
        <td> Type of Component</td>
        <td>'PointerClock'</td>
    </tr>
</table>

![](/assets/pointerClock01.png)




