---
layout: post
---

<style type="text/css">
    details {
        display: block;
    }
</style>

# English:

Time Hud (nTime):

Features:
<br>Displays Time (In Denmark or UTC)
<br>Nice Design
<br>Automatically Calibrates for your Resolution

<!-- <details>

<summary>
	Code
</summary>

```


@name Time Hud
@inputs E:wirelink
 
W = egpScrW(owner())
H = egpScrH(owner())
 
#remove the "+ 1" v (without quotations marks) to make it UTC
Hrs = (time("hour") + 1)
 
interval(1000)
E:egpText(3,"",vec2(W/2,H-49)) E:egpAlign(3,1,1) E:egpSize(3,60.5) E:egpColor(3,100,100,100,200)
E:egpText(4,"",vec2(W/2,H-51)) E:egpAlign(4,1,1) E:egpSize(4,60)
E:egpText(5,"nTime",vec2(W/2,H-21)) E:egpAlign(5,1,1) E:egpSize(5,16) E:egpColor(5,200,200,200,85)
 
if(time("min") <= 9) {
    if(Hrs <= 9) {
    E:egpSetText(3,"0"+Hrs+":0"+time("min")+"")
    E:egpSetText(4,"0"+Hrs+":0"+time("min")+"")
    } elseif(Hrs > 9) {
    E:egpSetText(3,""+Hrs+":0"+time("min")+"")
    E:egpSetText(4,""+Hrs+":0"+time("min")+"")
    }
   
} elseif(time("min") > 9) {
    if(Hrs <= 9) {
    E:egpSetText(3,"0"+Hrs+":"+time("min")+"")
    E:egpSetText(4,"0"+Hrs+":"+time("min")+"")
    } elseif(Hrs > 9) {
    E:egpSetText(3,""+Hrs+":"+time("min")+"")
    E:egpSetText(4,""+Hrs+":"+time("min")+"")
    }
}
 
E:egpRoundedBox(1, vec2(W/2,H-50), vec2(300,75))
E:egpRoundedBoxOutline(2, vec2(W/2,H-50), vec2(300,75))
E:egpColor(1, 0,0,0,135)
E:egpColor(2, 0,0,0,200)


```

</details> -->

[Pastebin][1]

<br>Images(Screenshots) =

None

# Danish:

Time Hud (nTime):

Funktioner:
<br>Viser Tiden (I Danmark eller UTC)
<br>Fedt Design
<br>Automatisk Kalibrer sig til dit spil' størrelse.

<!-- <details>

    <summary>Kode</summary>

```


@name Time Hud
@inputs E:wirelink
 
W = egpScrW(owner())
H = egpScrH(owner())
 
#remove the "+ 1" v (without quotations marks) to make it UTC
Hrs = (time("hour") + 1)
 
interval(1000)
E:egpText(3,"",vec2(W/2,H-49)) E:egpAlign(3,1,1) E:egpSize(3,60.5) E:egpColor(3,100,100,100,200)
E:egpText(4,"",vec2(W/2,H-51)) E:egpAlign(4,1,1) E:egpSize(4,60)
E:egpText(5,"nTime",vec2(W/2,H-21)) E:egpAlign(5,1,1) E:egpSize(5,16) E:egpColor(5,200,200,200,85)
 
if(time("min") <= 9) {
    if(Hrs <= 9) {
    E:egpSetText(3,"0"+Hrs+":0"+time("min")+"")
    E:egpSetText(4,"0"+Hrs+":0"+time("min")+"")
    } elseif(Hrs > 9) {
    E:egpSetText(3,""+Hrs+":0"+time("min")+"")
    E:egpSetText(4,""+Hrs+":0"+time("min")+"")
    }
   
} elseif(time("min") > 9) {
    if(Hrs <= 9) {
    E:egpSetText(3,"0"+Hrs+":"+time("min")+"")
    E:egpSetText(4,"0"+Hrs+":"+time("min")+"")
    } elseif(Hrs > 9) {
    E:egpSetText(3,""+Hrs+":"+time("min")+"")
    E:egpSetText(4,""+Hrs+":"+time("min")+"")
    }
}
 
E:egpRoundedBox(1, vec2(W/2,H-50), vec2(300,75))
E:egpRoundedBoxOutline(2, vec2(W/2,H-50), vec2(300,75))
E:egpColor(1, 0,0,0,135)
E:egpColor(2, 0,0,0,200)


```

</details> -->

[Pastebin][1]

<br>Billeder(Screenshots) =

Ingen

[1]: https://pastebin.com/XQYGMZ2B