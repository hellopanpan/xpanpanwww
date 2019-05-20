<template>
  <div class="showAll">
    <div class="page1 page">
      <div class="animate load animate1 " :class="showFlag?'show': 'hide'" @click.stop="changeStatus">
        <div class="line">
          <canvas class="line1" ref="line1" width="2px" height="520px">
          </canvas>
        </div>
        <div class="top">
          <div class="caret1">
          </div>
          <div class="caret2">
          </div>
          <div class="caret3">
            <canvas class="canvas1" width="250px" height="250px">
            </canvas>
          </div>
          
        </div>
        <div class="meddile">
          <div class="pic">
            <canvas class="canvas2_1" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_2" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_3" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_4" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_5" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_6" width="240px" height="240px" >
            </canvas>
          </div>
          
          <div class="play">
          </div>
          <div class="cen">
            <div class="center1">
              <h4>100度电商网站</h4>
              <p>2016.4</p>
            </div>
            <div class="side1">
            </div>
            <div class="side2">
            </div>
          </div>
        </div>
        <div class="bottom ">
          <div class="fan1">
            <img src="@/assets/images/fan1.png">
            <img src="@/assets/images/fan1-1.png">
          </div>
          <div class="fan2">
          </div>
          <div class="fan3">
            <img src="~@/assets/images/fan3-1.png">
          </div>
          
          <div class="fan4">
          </div>
          <div class="fan5">
          </div>
          <div class="fan6">
          </div>
          <div class="canvas3">
            <canvas class="canvas3_3" width="520px" height="520px">
            </canvas>
          </div>
          <div class="fan7">
            <span>2013</span>
            <span>2014</span>
            <span>2015</span>
            <span>2016</span>
            <span>2017</span>
          </div>
          <div class="fan8">
            <p>100度电商网站</p>
          </div>
          <div class="canvas4">
            <img class="img1s" src="~@/assets/images/xpan1-1s.png" style="display:none"/>
            <img class="img2s" src="~@/assets/images/xpan1-2s.png" style="display:none"/>
            <img class="img3s" src="~@/assets/images/xpan1-3s.png" style="display:none"/>
            <img class="img4s" src="~@/assets/images/xpan1-4s.png" style="display:none"/>
            <canvas class="canvas4_4" width="57px" height="96px">
            </canvas>
            <canvas class="canvas5" width="57px" height="72px">
            </canvas>
            <canvas class="canvas6" width="57px" height="77px">
            </canvas>
            <canvas class="canvas7" width="57px" height="93px">
            </canvas>
          </div>
        </div>
      </div>
    </div>
    <div class="page1 page">
      <div class="animate load animate1 " :class="showFlag?'show': 'hide'" @click.stop="changeStatus">
        <div class="line">
          <canvas class="line1" ref="line1" width="2px" height="520px">
          </canvas>
        </div>
        <div class="top">
          <div class="caret1">
          </div>
          <div class="caret2">
          </div>
          <div class="caret3">
            <canvas class="canvas1" width="250px" height="250px">
            </canvas>
          </div>
          
        </div>
        <div class="meddile">
          <div class="pic">
            <canvas class="canvas2_1" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_2" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_3" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_4" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_5" width="240px" height="240px" >
            </canvas>
            <canvas class="canvas2_6" width="240px" height="240px" >
            </canvas>
          </div>
          
          <div class="play">
          </div>
          <div class="cen">
            <div class="center1">
              <h4>100度电商网站</h4>
              <p>2016.4</p>
            </div>
            <div class="side1">
            </div>
            <div class="side2">
            </div>
          </div>
        </div>
        <div class="bottom ">
          <div class="fan1">
            <img src="@/assets/images/fan1.png">
            <img src="@/assets/images/fan1-1.png">
          </div>
          <div class="fan2">
          </div>
          <div class="fan3">
            <img src="~@/assets/images/fan3-1.png">
          </div>
          
          <div class="fan4">
          </div>
          <div class="fan5">
          </div>
          <div class="fan6">
          </div>
          <div class="canvas3">
            <canvas class="canvas3_3" width="520px" height="520px">
            </canvas>
          </div>
          <div class="fan7">
            <span>2013</span>
            <span>2014</span>
            <span>2015</span>
            <span>2016</span>
            <span>2017</span>
          </div>
          <div class="fan8">
            <p>100度电商网站</p>
          </div>
          <div class="canvas4">
            <img class="img1s" src="~@/assets/images/xpan2-1s.png" style="display:none"/>
            <img class="img2s" src="~@/assets/images/xpan2-2s.png" style="display:none"/>
            <img class="img3s" src="~@/assets/images/xpan2-3s.png" style="display:none"/>
            <img class="img4s" src="~@/assets/images/xpan2-4s.png" style="display:none"/>
            <canvas class="canvas4_4" width="57px" height="96px">
            </canvas>
            <canvas class="canvas5" width="57px" height="72px">
            </canvas>
            <canvas class="canvas6" width="57px" height="77px">
            </canvas>
            <canvas class="canvas7" width="57px" height="93px">
            </canvas>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

  export default {
    name:'',
    props:[''],
    data () {
      return {
        showFlag: false,
      };
    },
    methods: {
      // 改状态
      changeStatus() {
        this.showFlag = !this.showFlag
      },
      // 绘制一条细线
      drawLine() {
        var ocLines= document.getElementsByClassName("line1");
        for (var i = 0; i< ocLines.length; i++) {
          var oGcLine=ocLines[i].getContext("2d");
          oGcLine.strokeStyle="#00bebe";
          oGcLine.beginPath();
          oGcLine.moveTo(1,0);
          oGcLine.lineTo(1,520);
          oGcLine.stroke();
        }
      },
      // 绘制3条弧线
      drawCanvas1() {
        var oc1s=document.getElementsByClassName("canvas1");
        for (var i = 0; i< oc1s.length; i++) {
          var oGc1=oc1s[i].getContext("2d");
          var x=125;
          var y=125;
          var r=120;
          oGc1.beginPath();
          oGc1.lineWidth=8;
          oGc1.strokeStyle="white";
          oGc1.arc(x,y,r,-60*Math.PI/180,0*Math.PI/180,false);
          oGc1.stroke();
          oGc1.beginPath();
          oGc1.arc(x,y,r,60*Math.PI/180,120*Math.PI/180,false);
          oGc1.stroke();
          oGc1.beginPath();
          oGc1.arc(x,y,r,180*Math.PI/180,240*Math.PI/180,false);
          oGc1.stroke();
        }
        
      },
      //绘制6条（2种）弧线，2小圆
      drawCanvasCircle() {
        var oc2_1s=document.getElementsByClassName("canvas2_1");
        for (var ii = 0; ii< oc2_1s.length; ii++ ) {
          var oGc2_1 = oc2_1s[ii].getContext("2d");
          var x=120;
          var y=120;
          //1
          var r=116;
          oGc2_1.beginPath();
          oGc2_1.lineWidth=8;
          oGc2_1.globalAlpha=0.9;
          oGc2_1.strokeStyle="#00bebe";
          oGc2_1.arc(x,y,r,-110*Math.PI/180,-70*Math.PI/180,false);
          oGc2_1.stroke();
          oGc2_1.beginPath();
          oGc2_1.arc(x,y,r,10*Math.PI/180,50*Math.PI/180,false);
          oGc2_1.stroke();
          oGc2_1.beginPath();
          oGc2_1.arc(x,y,r,130*Math.PI/180,170*Math.PI/180,false);
          oGc2_1.stroke();
          
          
          //2
          var oc2_2=document.getElementsByClassName("canvas2_2")[ii];
          var oGc2_2=oc2_2.getContext("2d");
          
          var x=120;
          var y=120;
          r=113;
          oGc2_2.strokeStyle="#00bebe";
          oGc2_2.lineWidth=2;
          oGc2_2.beginPath();
          oGc2_2.arc(x,y,r,-60*Math.PI/180,-0*Math.PI/180,false);
          oGc2_2.stroke();
          oGc2_2.beginPath();
          oGc2_2.arc(x,y,r,60*Math.PI/180,120*Math.PI/180,false);
          oGc2_2.stroke();
          oGc2_2.beginPath();
          oGc2_2.arc(x,y,r,180*Math.PI/180,240*Math.PI/180,false);
          oGc2_2.stroke();
          //3
          var oc2_3=document.getElementsByClassName("canvas2_3")[ii];
          var oGc2_3=oc2_3.getContext("2d");
          var x=120;
          var y=120;
          oGc2_3.beginPath();
          
          oGc2_3.globalAlpha=0.5;
          r=107;
          oGc2_3.lineWidth=6;
          oGc2_3.strokeStyle="#88c0c0";
          oGc2_3.arc(x,y,r,0*Math.PI/180,-360*Math.PI/180,false);
          oGc2_3.stroke();
          
          //4
          var oc2_4=document.getElementsByClassName("canvas2_4")[ii];
          var oGc2_4=oc2_4.getContext("2d");
          var x=120;
          var y=120;
          oGc2_4.beginPath();
          r=101;
          oGc2_4.lineWidth=3;
          oGc2_4.strokeStyle="#88c0c0";
          oGc2_4.globalAlpha=0.8;
          oGc2_4.arc(x,y,r,0*Math.PI/180,-360*Math.PI/180,false);
          oGc2_4.stroke();
          //5
          var oc2_5=document.getElementsByClassName("canvas2_5")[ii];
          var oGc2_5=oc2_5.getContext("2d");
          var x=120;
          var y=120;
          oGc2_5.lineWidth=3;
          oGc2_5.strokeStyle="#00bebe";
          r=96;
          for(var i=0;i<180;i++){
            oGc2_5.beginPath();
            oGc2_5.arc(x,y,r,(2*i)*Math.PI/180,(2*i+1)*Math.PI/180,false);
            oGc2_5.stroke();
          }
          //6
          (()=> {
            var oc2_6=document.getElementsByClassName("canvas2_6")[ii];
            var oGc2_6=oc2_6.getContext("2d");
            var x=120;
            var y=120;
            var obj=oGc2_6.createLinearGradient(0,0,240,240);
            obj.addColorStop(0,"#88c0c0");
            obj.addColorStop(1,"#00bebe");
            
            oGc2_6.fillStyle=obj;
            oGc2_6.globalAlpha=0.3;
            var timer=null;
            var i=0;
            timer=setInterval(()=>{
              oGc2_6.beginPath();
              r=90;
              oGc2_6.arc(x,y,r,(i*45+2)*Math.PI/180,(i*45+45-2)*Math.PI/180,false);
              r=44;
              oGc2_6.arc(x,y,r,(i*45+45-2)*Math.PI/180,(i*45+2)*Math.PI/180,true);
              oGc2_6.closePath();
              oGc2_6.fill();
              if(i>=7){
                clearInterval(timer);
                timer=null;
              };
              i++;
            },150);
          })(ii)
          
        }
        
      },
      //绘制半边弧面
      drawCanvas3() {
        var oc3s=document.getElementsByClassName("canvas3_3");
        for (var i = 0; i< oc3s.length; i++) {
          var oGc3=oc3s[i].getContext("2d");
          var x=260;
          var y=260;
          var r=200;
          oGc3.beginPath();
          oGc3.fillStyle="rgba(0,113,177,0.5)";
          oGc3.arc(x,y,r,30*Math.PI/180,-130*Math.PI/180,true);
          r=160;
          oGc3.arc(x,y,r,-130*Math.PI/180,30*Math.PI/180,false);
          oGc3.fill();
        }
      },
      //绘制图片img1
      drawCanvas4() {
        var oc4s=document.getElementsByClassName("canvas4_4");
        for (var ii = 0; ii< oc4s.length; ii++ ) {
          var imgs=document.getElementsByClassName("img1s");
          // 闭包
          ((ii) => {
            imgs[ii].onload = () => {
              var oGc4=oc4s[ii].getContext("2d");
              var pat=oGc4.createPattern(imgs[ii],"repeat");
              oGc4.fillStyle=pat;
              oGc4.beginPath();
              oGc4.moveTo(26,0);
              oGc4.lineTo(57,31);
              oGc4.lineTo(57,80);
              oGc4.lineTo(49,96);
              oGc4.lineTo(0,75);
              oGc4.lineTo(0,31);
              oGc4.closePath();
              oGc4.fill();
            };
          })(ii)
          
        }
      },
      // 绘制图片img2
      drawCanvas5() {
        var oc5s = document.getElementsByClassName("canvas5");
        for (var ii = 0; ii< oc5s.length; ii++ ) {
          ((ii)=> {
            var oGc5 = oc5s[ii].getContext("2d");
            var img = document.getElementsByClassName("img2s")[ii];
            img.onload = () => {
              var pat=oGc5.createPattern(img,"repeat");
              oGc5.fillStyle=pat;
              oGc5.beginPath();
              oGc5.moveTo(8,0);
              oGc5.lineTo(57,20);
              oGc5.lineTo(57,77);
              oGc5.lineTo(0,77);
              oGc5.lineTo(0,19);
              oGc5.closePath();
              oGc5.fill();
            };
          })(ii)
        }
      },
      //绘制图片img3
      drawCanvas6() {
        var oc6s=document.getElementsByClassName("canvas6");
        for (var ii = 0; ii< oc6s.length; ii++ ) {
          ((ii) => {
            var oGc6=oc6s[ii].getContext("2d");
            var img=document.getElementsByClassName("img3s")[ii];
              img.onload = () => {
                var pat=oGc6.createPattern(img,"repeat");
                oGc6.fillStyle=pat;
                oGc6.beginPath();
                oGc6.moveTo(0,0);
                oGc6.lineTo(57,0);
                oGc6.lineTo(57,58);
                oGc6.lineTo(4,77);
                oGc6.lineTo(0,72);
                oGc6.closePath();
                oGc6.fill();
            };
          })(ii)
        }
      },
      //绘制图片img4
      drawCanvas7() {
        var oc7s=document.getElementsByClassName("canvas7");
        for (var ii = 0; ii< oc7s.length; ii++ ) {
          ((ii) => {
            var oGc7=oc7s[ii].getContext("2d");
            var img=document.getElementsByClassName("img4s")[ii];
            img.onload = () => {
              var pat=oGc7.createPattern(img,"repeat");
              oGc7.fillStyle=pat;
              oGc7.beginPath();
              oGc7.moveTo(46,0);
              oGc7.lineTo(57,22);
              oGc7.lineTo(57,59);
              oGc7.lineTo(21,93);
              oGc7.lineTo(0,69);
              oGc7.lineTo(0,22);
              oGc7.closePath();
              oGc7.fill();
            }
          })(ii)
          
        }
      }
    },
    mounted() {
      this.drawCanvas1();
      this.drawLine();
      this.drawCanvasCircle();
      this.drawCanvas3();
      this.drawCanvas4();
      this.drawCanvas5();
      this.drawCanvas6();
      this.drawCanvas7();
    },

  }

</script>
<style lang='less' scoped>
  @-webkit-keyframes move1{
    0%{transform:rotateZ(0deg)}
    50%{transform:rotateZ(180deg)}
    100%{transform:rotateZ(360deg)}
  }
  @-webkit-keyframes hide1{
    0%{transform:scale(1)}
    100%{transform:scale(0)}
  }
  @-webkit-keyframes showTop{
    0%{transform:scale(0) translateZ(0px) }
    100%{transform:scale(1) translateZ(180px)}
  }
  @-webkit-keyframes hideTop{
    0%{transform:scale(1) translateZ(180px)}
    100%{transform:scale(0) translateZ(0px) }
  }
  @-webkit-keyframes showBottom{
    0%{transform:translateZ(0px) }
    100%{transform:translateZ(-180px)}
  }
  @-webkit-keyframes hideBottom{
    0%{transform:translateZ(-180px)}
    100%{transform:translateZ(0px) }
  }
  @-webkit-keyframes show1{
    0%{transform:scale(0)}
    100%{transform:scale(1)}
  }
  @-webkit-keyframes rotate1{
    0%{transform:rotate(0deg)}
    25%{transform:rotate(60deg)}
    50%{transform:rotate(120deg)}
    75%{transform:rotate(60deg)}
    100%{transform:rotate(0deg)}
  }
  @-webkit-keyframes rotate2{
    0%{transform:rotate(0deg)}
    25%{transform:rotate(-60deg)}
    50%{transform:rotate(-120deg)}
    75%{transform:rotate(-60deg)}
    100%{transform:rotate(0deg)}
  }
  @-webkit-keyframes showlight{
    0%{opacity:0.3}
    20%{opacity:1;}
    50%{opacity:0.2;}
    70%{opacity:1;}
    90%{opacity:0.5;}
    100%{opacity:1;}
  }
  .load .top, .load .bottom .fan1 img,.load .bottom .fan2,.load .bottom .fan3,.load .bottom .fan4,.load .bottom .fan5,.load .bottom .fan6,.load .bottom .fan7,.load .bottom .fan8,.load .bottom .canvas3,.load .bottom .canvas4 canvas{transform:scale(0);}
  .showAll{
    width:100%;position:absolute;top:-20px;transition:0.8s; 
    .light {position:absolute;width:1800px;height:200px;top:340px;left:560px;z-index:-1;opacity:1;}
    .light.showlight{animation:0.5s showlight;opacity:1}
    .light .row{float:left;width:520px;height:2px;position:relative;box-shadow:0px 0px 6px 0px #25f7fc;}
    .light .row .case1{width:100%;height:100%;background:url('~@/assets/images/lightbg.png') no-repeat;position:absolute;top:0}
    .light .row .case2{width:100%;height:100%;position:absolute;background:#25f7fc;opacity:0.6;top:0}
    .light .row1{transform:rotateZ(-21deg);}
    .light .row2{transform:rotateZ(21deg);}
    .light .row3{transform:rotateZ(-21deg);}
  }
  .page{float:left;transition:0.6s;z-index: 10;}
  .page1{transform:translateY(200px);}
  .show{transform:translateY(50px) rotateX(45deg) rotateY(-18deg) translateZ(300px);}
  .animate{
    width:520px;height:520px;top:0px;perspective:1600px;transform-style:preserve-3d;transition:1s;cursor:pointer;position:relative;z-index:1;
    .line1{position:absolute;top:0px;left:259px;transform:rotateX(90deg)}
    .top{width:280px;height:280px;position:absolute;top:120px;left:120px;z-index:3;}
    .top .caret1{width:84px;height: 84px; position:absolute;left:98px; top: 98px; background: url('~@/assets/images/circle.png') no-repeat; background-position: -587px -803px;animation:5s move1 linear infinite;transition:0.2s all linear; }
    .top .caret2{width:242px; height: 242px; position:absolute;left:19px; top: 19px; background: url('~@/assets/images/circle.png') no-repeat ;background-position:-517px -429px;animation:5s move1 linear infinite; }
    .top .caret3{position:absolute;top:15px;left:15px;top: 15px;width:250px;transform:scale(1);height:250px;animation:5s move1 linear infinite;transition:0.2s all linear;}
  }
  .show .top{animation: 0.5s showTop linear; transform:scale(1) translateZ(180px)}
  .hide .top{animation: 0.5s hideTop linear; transform:scale(0) translateZ(0px)}
  .hide .caret1{opacity:1}
  .hide  .caret3{opacity:1}
  .show .caret3{opacity:1}

  .meddile{
    height:240px;width:332px;position:absolute;overflow:hidden;top:140px;left:94px;z-index:100;
    .pic{width:240px;height:240px;position:absolute;top:0;left:46px;}
    .play{width:76px;height:76px;position:absolute;top:82px;left:128px;background:url('~@/assets/images/play.png') no-repeat;}
    .center1{transform:scale(0);width:272px;height:86px;color:#fff;position:absolute;top:77px;text-align:center;left:30px;transform-origin:center center;background:url('~@/assets/images/textbj.png') no-repeat left center;transition:0.4s all linear;}
    .center1 h4{line-height:20px;padding:20px 0 10px 0;margin:0;font-weight:normal;font-size:18px;}
    .center1 p{font-size:16px;}
    .side1{width:66px;height:50px;position:absolute;top:95px;left:-66px;background:url('~@/assets/images/bian.png') no-repeat left center;transition:0.3s all linear;}
    .side2{width:66px;height:50px;position:absolute;top:95px;right:-66px;background:url('~@/assets/images/bian.png') no-repeat right center;transition:0.3s all linear;}
    .pic canvas{position:absolute;top:0;left:0;}
  }

  .load .meddile .pic canvas:nth-of-type(1){transform:rotate(0deg);animation:rotate1 1s linear;}
  .load .meddile .pic canvas:nth-of-type(2){transform:rotate(0deg);animation:rotate1 1.2s linear;}
  .bottom{
    height:520px;width:520px;position:absolute;top:0;left:0;z-index:3;
    .fan1{width:130px;height:130px;position:absolute;top:195px;left:195px;animation:6s move1 infinite linear;}
    .fan1 img{transition:0.3s all linear;}
    .fan1 img:nth-of-type(1){position:absolute;top:0px;left:-1px;transform-origin:center right;}
    .fan2{width:154px;height:154px;position:absolute;top:183px;left:183px;background:url('~@/assets/images/fan2.png');transition:0.35s all linear;}
    .fan1 img:nth-of-type(2){position:absolute;top:0px;left:65px;transform-origin:center left;}
    .fan3{width:236px;height:236px;position:absolute;top:142px;left:142px;background:url('~@/assets/images/fan3.png');text-align:center;transition:0.4s all linear;}
    .fan3 img{margin:2px 0;}
    .fan4{width:266px;height:266px;position:absolute;top:127px;left:127px;background:url('~@/assets/images//fan4.png');text-align:center;transition:0.45s all linear;}
    .fan5{width:312px;height:312px;position:absolute;top:104px;left:104px;background:url('~@/assets/images/fan5.png');text-align:center;transition:0.5s all linear;}
    .fan6{width:182px;height:320px;position:absolute;top:100px;right:20px;background:url('~@/assets/images/fan6.png');transform-origin:-58px 160px;transition:0.55s all linear;}
    .fan7{width:190px;height:18px;line-height:18px;position:absolute;top:251px;left:260px;transition:0.65s all linear;transform-origin:center left;}
    .fan7 span{position:absolute;top:0;right:0;width:190px;color:rgb(170,233,253);font-size:12px;display:block;text-align:right;transform-origin:center left;transition:0.65s all linear;}
    .fan7 span:nth-of-type(1){transform:rotateZ(-40deg);}
    .fan7 span:nth-of-type(2){transform:rotateZ(-20deg);}
    .fan7 span:nth-of-type(3){transform:rotateZ(0deg);}
    .fan7 span:nth-of-type(4){transform:rotateZ(20deg);}
    .fan7 span:nth-of-type(5){transform:rotateZ(40deg);}
    .fan8{width:186px;height:215px;transform-origin:93px -45px;line-height:295px;text-align:center;position:absolute;top:300px;left:167px; background:url('~@/assets/images/fan8.png');color:#e9f6fe;font-size:14px;transition:0.4s all linear;}
    .canvas3{width:520px;height:520px;position:absolute;top:0;left:0;transition:0.35s all linear;}
    .canvas4{width:520px;height:260px;position:absolute;top:0;left:0;}
    .canvas4_4{width:57px;height:96px;position:absolute;top:109px;left:68px;transition:0.35s all linear;transform-origin:192px 151px;}
    .canvas5{width:57px;height:72px;position:absolute;top:183px;left:39px;transition:0.45s all linear;transform-origin:221px 77px;}
    .canvas6{width:57px;height:77px;position:absolute;top:266px;left:44px;transition:0.5s all linear;transform-origin:212px -6px;}
    .canvas7{width:57px;height:93px;position:absolute;top:322px;left:71px;transition:0.55s all linear;transform-origin:189px -62px;}
    .canvas44-4:nth-of-type(1){width:57px;height:96px;position:absolute;top:109px;left:68px;transition:0.35s all linear;transform-origin:192px 151px;}
    .canvas44-4:nth-of-type(2){width:57px;height:72px;position:absolute;top:183px;left:39px;transition:0.45s all linear;transform-origin:221px 77px;}
    .canvas44-4:nth-of-type(3){width:57px;height:77px;position:absolute;top:266px;left:44px;transition:0.5s all linear;transform-origin:212px -6px;}
    .canvas44-4:nth-of-type(4){width:57px;height:93px;position:absolute;top:322px;left:71px;transition:0.55s all linear;transform-origin:189px -62px;}
    .canvas33-4:nth-of-type(1){width:57px;height:96px;position:absolute;top:109px;left:68px;transition:0.35s all linear;transform-origin:192px 151px;}
    .canvas33-4:nth-of-type(2){width:57px;height:72px;position:absolute;top:183px;left:39px;transition:0.45s all linear;transform-origin:221px 77px;}
    .canvas33-4:nth-of-type(3){width:57px;height:77px;position:absolute;top:266px;left:44px;transition:0.5s all linear;transform-origin:212px -6px;}
    .canvas33-4:nth-of-type(4){width:57px;height:93px;position:absolute;top:322px;left:71px;transition:0.55s all linear;transform-origin:189px -62px;}
    .canvas22-4:nth-of-type(1){width:57px;height:96px;position:absolute;top:109px;left:68px;transition:0.35s all linear;transform-origin:192px 151px;}
    .canvas22-4:nth-of-type(2){width:57px;height:72px;position:absolute;top:183px;left:39px;transition:0.45s all linear;transform-origin:221px 77px;}
    .canvas22-4:nth-of-type(3){width:57px;height:77px;position:absolute;top:266px;left:44px;transition:0.5s all linear;transform-origin:212px -6px;}
    .canvas22-4:nth-of-type(4){width:57px;height:93px;position:absolute;top:322px;left:71px;transition:0.55s all linear;transform-origin:189px -62px;}
  }
  .hide .bottom .fan1 img,.hide .bottom .fan2,.hide .bottom .fan3,.hide .bottom .fan4,.hide .bottom .fan5,.hide .bottom .fan6,.hide .bottom .fan7,.hide .bottom .fan8,.hide .bottom .canvas3,.hide .bottom .canvas4 canvas{transform:scale(0);}
  .show .bottom{animation: 0.5s showBottom linear;transform:translateZ(-180px)}
  .show .bottom .fan1 img,.show .bottom .fan2,.show .bottom .fan3,.show .bottom .fan4,.show .bottom .fan5,.show .bottom .fan6,.show .bottom .fan7,.show .bottom .fan8,.show .bottom .canvas3,.show .bottom .canvas4 canvas{transform:scale(1);}
  .hide .bottom{animation: 0.5s hideBottom linear;transform:translateZ(0px)}
</style>