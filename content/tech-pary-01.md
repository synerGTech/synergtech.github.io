Title: SynerG Tech Party 01
Date: 2016-09-29
Authors: lihas
Summary: Very first tech party of synerG group. UEFI, and samosa!

<center>
![SynerG Tech Party](https://cloud.githubusercontent.com/assets/1687568/18940459/027c5614-8626-11e6-95fc-8fef60eee9ca.png "synerG Tech Party")
</center>

EAT-CODE-REPEAT

### Wait, what?

Tech party is a time to get our hands dirty with a new piece of technology. There is only one limitation.

* It has to be cool [^1]


### This week's plan

- Hello world! UEFI application
- Simple UEFI client server network application
- Measure N/W throughput. Is it better than when OS is running?
- Measure power consumption of C-S application with, and without OS.

### Why is it cool?

- Pre-boot environment, no OS (may) means better performance for (some) code
- Feature rich - supports networking
- Many projects we are working on are concerned with getting OS out of the way, UEFI may give some ideas

### Please vote for a Preferred time, for this weeks party
<br />
<div id="qp_all829215" style="width:100%;"><STYLE>#qp_main829215 .qp_btna:hover input {background:rgb(150,150,150)!important}</STYLE><div id="qp_main829215" fp='B65946bA-33' results=0 style="border-radius:6px;border:1px solid rgb(150,150,150);margin:0 auto;padding:10px;background:rgb(255,255,255);box-sizing:border-box"><div style="border-radius:6px;font-family:Arial;font-size:12px;font-weight:bold;background-color:rgb(44,44,44);color:rgb(255,255,255);margin-bottom:10px"><div style="padding:10px">Preferred time for party</div></div><form id="qp_form829215" action="//www.poll-maker.com/results829215xB65946bA-33" method="post" target="_blank" style="display:inline;margin:0px;padding:0px"><div style="border-radius:6px"><input type=hidden name="qp_d829215" value="42642.8272685131-42642.827249959"><div style="display:block;font-family:Arial;font-size:12px;color:rgb(0,0,0);padding-top:5px;padding-bottom:5px;clear:both" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="display:block;padding-left:30px;cursor:inherit"><input style="float:left;width:18px;margin-left:-25px;margin-top:-2px;padding:0px;height:18px;-webkit-appearance:checkbox;" name="qp_v829215" type="checkbox" value="1" />Saturday 2200 Hrs</span></div><div style="display:block;font-family:Arial;font-size:12px;color:rgb(0,0,0);padding-top:5px;padding-bottom:5px;clear:both" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="display:block;padding-left:30px;cursor:inherit"><input style="float:left;width:18px;margin-left:-25px;margin-top:-2px;padding:0px;height:18px;-webkit-appearance:checkbox;" name="qp_v829215" type="checkbox" value="2" />Saturday 2300 Hrs</span></div><div style="display:block;font-family:Arial;font-size:12px;color:rgb(0,0,0);padding-top:5px;padding-bottom:5px;clear:both" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="display:block;padding-left:30px;cursor:inherit"><input style="float:left;width:18px;margin-left:-25px;margin-top:-2px;padding:0px;height:18px;-webkit-appearance:checkbox;" name="qp_v829215" type="checkbox" value="3" />Saturday 2400 Hrs</span></div><div style="display:block;font-family:Arial;font-size:12px;color:rgb(0,0,0);padding-top:5px;padding-bottom:5px;clear:both" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="display:block;padding-left:30px;cursor:inherit"><input style="float:left;width:18px;margin-left:-25px;margin-top:-2px;padding:0px;height:18px;-webkit-appearance:checkbox;" name="qp_v829215" type="checkbox" value="999" />Other</span></div><div id="qp_ot829215" style="display:block;font-family:Arial;font-size:12px;color:rgb(0,0,0);padding-top:5px;padding-bottom:5px;clear:both"><div style="padding-left:33px">Please Specify: <input style="width:100%;position:relative;top:2px" name='qp_other829215' type=text value=''></div></div></div><div style="clear:both;text-align:left;margin:0 auto 2em auto"><a style="text-decoration:none" class="qp_btna" href="#"><input name="qp_b829215" style="min-width:7em;padding:0.5em;margin-top:5px;margin-right:5px;border-radius:10px;border:1px solid rgb(150,150,150);font-family:Arial;font-size:12px;font-weight:bold;color:rgb(0,0,0);cursor:pointer;cursor:hand;background:rgb(200,200,200)" type="submit" btype="v" value="Vote" /></a><a style="text-decoration:none" class="qp_btna" href="#"><input name="qp_b829215" style="min-width:7em;padding:0.5em;margin-top:5px;margin-right:5px;border-radius:10px;border:1px solid rgb(150,150,150);font-family:Arial;font-size:12px;font-weight:bold;color:rgb(0,0,0);cursor:pointer;cursor:hand;background:rgb(200,200,200)" type="submit" btype="r" value="Results" /></a></div><a id="qp_a829215" style="float:right;font-family:Arial;font-size:10px;color:rgb(0,0,0);text-decoration:none" href="http://www.poll-maker.com">Poll Maker</a></form><div style="display:none"><div id="qp_rp829215" style="font-size:11px;width:5ex;text-align:right;overflow:hidden;position:absolute;right:5px;height:1.5em;line-height:1.5em"></div><div id="qp_rv829215" style="font-size:11px;width:0%;line-height:1.5em;text-align:right;color:#FFF;box-sizing:border-box;padding-right:3px"></div><div id="qp_rb829215" style="font-size:12px;color:rgb(255,255,255);display:block;font-size:12px;padding-right:10px 5px"></div><div id="qp_rva829215" style="background:#006FB9;border-color:#006FB9"></div><div id="qp_rvb829215" style="background:#163463;border-color:#163463"></div><div id="qp_rvc829215" style="background:#5BCFFC;border-color:#1481AB"></div></div></div></div><script src="//scripts.poll-maker.com/3012/scpolls.js" language="javascript"></script>

<br />

##Tech Party FAQs

### A 4-point Agenda

- Decide upon a technology, and hack
- Blog about it after the event
- The blog is intended to be a getting starting guide for the technology
- Upload code to github

### When?

Preferably on weekends, when people have some free time, and they are in a mood to have fun.

### Agenda?

Decide the technology a week in advance. Propose topics, take poll, volunteer.

### What it is and what it is not

This should not be a 1:many interaction, in which one teaches, and others listen. Preferably a group effort, where all contribute equally.

### But you mentioned volunteer?

Yes, there should be a volunteer who sends out invitation, manages logitics, and uploads a short descrition of the event, once it ends. This discription should preferably be in the form of a getting started guide for the technology.


[^1]: https://goo.gl/IHFkh3
