<template>
  <div class="index-contain">
    <div class="cell">
      <h1>卡券1</h1>
      <div class="hollow-one-circle"></div>
      <div class="code">
        <div class="pre" >
          <pre>
            .hollow-one-circle {
              width: 100px;
              height: 100px;
              position: relative;
              background: radial-gradient(circle at 50px 0, transparent 10px, #00adb5 0) top left/100px 100% no-repeat;
              filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
            }
          </pre>
        </div>
      </div>
    </div>
    <div class="cell">
      <h1>卡券2</h1>
      <div class="hollow-two-circles"></div>
      <div class="hollow-two-circles_vertical"></div>
      <div class="code">
        <div class="pre" >
          <pre>
            .hollow-two-circles {
              width: 300px;
              height: 100px;
              position: relative;
              background: radial-gradient(circle at right top, transparent 10px, #00adb5 0) top left / 60px 51% no-repeat,
                radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) bottom left /60px 51% no-repeat,
                radial-gradient(circle at left top, transparent 10px, #eeeeee 0) top right /240px 51% no-repeat,
                radial-gradient(circle at left bottom, transparent 10px, #eeeeee 0) bottom right /240px 51% no-repeat;
               filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
            }

            .hollow-two-circles::after {
              content: '';
              height: 80px;
              border: 1px dashed #fff;
              position: absolute;
              left: 60px;
              top: 0;
              bottom: 0;
              margin: auto;
            }
            ---------------------------
            .hollow-two-circles_vertical {
              width: 300px;
              height: 100px;
              position: relative;
              background: radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) top right / 51% 60px no-repeat,
                radial-gradient(circle at left bottom, transparent 10px, #00adb5 0) top left / 51% 60px no-repeat,
                radial-gradient(circle at right top, transparent 10px, #eeeeee 0) bottom right / 51% 40px no-repeat,
                radial-gradient(circle at left top, transparent 10px, #eeeeee 0) bottom left / 51% 40px no-repeat;
               filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
            }

            .hollow-two-circles_vertical::after {
              content: '';
              width: 280px;
              border: 1px dashed #fff;
              position: absolute;
              left: 0;
              right: 0;
              top: 60px;
              margin: auto;
            }
          </pre>
        </div>
      </div>
    </div>
    <div class="cell">
      <h1>卡券3</h1>
      <div class="hollow-circles-left"></div>
      <div class="code">
        <div class="pre" >
          <pre>
            .hollow-circles-left {
              width: 300px;
              height: 100px;
              position: relative;
              background: #00adb5;
              margin-left: 10px;
              filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
            }
            .hollow-circles-left::after {
              content: '';
              position: absolute;
              height: 100%;
              width:5px;
              top: 0;
              left: -5px;
              background-image: linear-gradient(to bottom, #00adb5 5px, transparent 5px, transparent),
              radial-gradient(10px circle at 0px 10px, transparent 5px, #00adb5 5px);
              background-size: 5px 15px;
            }
          </pre>
        </div>
      </div>
    </div>
    <div class="cell">
      <h1>卡券4</h1>
      <div class="hollow-compose-many-circles"></div>
      <div class="hollow-compose-many-circles_left"></div>
      <div class="code">
        <div class="pre" >
          <pre>
            .hollow-compose-many-circles {
              width: 300px;
              height: 100px;
              position: relative;
              background: radial-gradient(circle at right top, transparent 10px, #00adb5 0) top left / 60px 51% no-repeat,
                radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) bottom left /60px 51% no-repeat,
                radial-gradient(circle at left top, transparent 10px, #eeeeee 0) top right /240px 51% no-repeat,
                radial-gradient(circle at left bottom, transparent 10px, #eeeeee 0) bottom right /240px 51% no-repeat;
               filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
            }

            .hollow-compose-many-circles::before {
              content: '';
              height: 80px;
              border: 1px dashed #fff;
              position: absolute;
              left: 60px;
              top: 0;
              bottom: 0;
              margin: auto;
            }

            .hollow-compose-many-circles::after {
              content: '';
              position: absolute;
              height: 100%;
              width:5px;
              top: 0;
              right: -5px;
              background-image: linear-gradient(to bottom, #eeeeee 5px, transparent 5px, transparent),
              radial-gradient(10px circle at 5px 10px, transparent 5px, #eeeeee 5px);
              background-size: 5px 15px;
              }
              --------------------------

            .hollow-compose-many-circles_left {
              width: 300px;
              height: 100px;
              position: relative;
              background: radial-gradient(circle at right top, transparent 10px, #00adb5 0) top left / 60px 51% no-repeat,
                radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) bottom left /60px 51% no-repeat,
                radial-gradient(circle at left top, transparent 10px, #eeeeee 0) top right /240px 51% no-repeat,
                radial-gradient(circle at left bottom, transparent 10px, #eeeeee 0) bottom right /240px 51% no-repeat;
               filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
            }

            .hollow-compose-many-circles_left::before {
              content: '';
              height: 80px;
              border: 1px dashed #fff;
              position: absolute;
              left: 60px;
              top: 0;
              bottom: 0;
              margin: auto;
            }

            .hollow-compose-many-circles_left::after {
              content: '';
              position: absolute;
              height: 100%;
              width:5px;
              top: 0;
              left: -5px;
              background-image: linear-gradient(to bottom, #00adb5 5px, transparent 5px, transparent),
              radial-gradient(10px circle at 0px 10px, transparent 5px, #00adb5 5px);
              background-size: 5px 15px;
              }
          </pre>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {

  data() {
    return {}

  }

};
</script>

<style lang="less">
h1 {
  font-size: 12px;
  padding-bottom: 3px;
  border-bottom: 1px solid #eee;
}
.pre {
  position: relative;
  background-color: #282c34;
  border-radius: 6px;
  pre {
    line-height: 1.4;
    padding: 10px 15px;
    margin: .85rem 0;
    border-radius: 6px;
    font-size: 8px;
    color: #f08d49;
    overflow: auto;
  }
}
.hollow-one-circle {
  width: 100px;
  height: 100px;
  position: relative;
  background: radial-gradient(circle at 50px 0, transparent 10px, #00adb5 0) top left/100px 100% no-repeat;
  filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
}

.hollow-two-circles {
  width: 300px;
  height: 100px;
  position: relative;
  background: radial-gradient(circle at right top, transparent 10px, #00adb5 0) top left / 60px 51% no-repeat,
    radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) bottom left /60px 51% no-repeat,
    radial-gradient(circle at left top, transparent 10px, #eeeeee 0) top right /240px 51% no-repeat,
    radial-gradient(circle at left bottom, transparent 10px, #eeeeee 0) bottom right /240px 51% no-repeat;
   filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
}

.hollow-two-circles::after {
  content: '';
  height: 80px;
  border: 1px dashed #fff;
  position: absolute;
  left: 60px;
  top: 0;
  bottom: 0;
  margin: auto;
}

.hollow-two-circles_vertical {
  margin-top: 20px;
  width: 300px;
  height: 100px;
  position: relative;
  background: radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) top right / 51% 60px no-repeat,
    radial-gradient(circle at left bottom, transparent 10px, #00adb5 0) top left / 51% 60px no-repeat,
    radial-gradient(circle at right top, transparent 10px, #eeeeee 0) bottom right / 51% 40px no-repeat,
    radial-gradient(circle at left top, transparent 10px, #eeeeee 0) bottom left / 51% 40px no-repeat;
   filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
}

.hollow-two-circles_vertical::after {
  content: '';
  width: 280px;
  border: 1px dashed #fff;
  position: absolute;
  left: 0;
  right: 0;
  top: 60px;
  margin: auto;
}

.hollow-circles-left {
  width: 300px;
  height: 100px;
  position: relative;
  background: #00adb5;
  margin-left: 10px;
  filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
}
.hollow-circles-left::after {
  content: '';
  position: absolute;
  height: 100%;
  width:5px;
  top: 0;
  left: -5px;
  background-image: linear-gradient(to bottom, #00adb5 5px, transparent 5px, transparent),
  radial-gradient(10px circle at 0px 10px, transparent 5px, #00adb5 5px);
  background-size: 5px 15px;
}

.hollow-compose-many-circles {
  width: 300px;
  height: 100px;
  position: relative;
  background: radial-gradient(circle at right top, transparent 10px, #00adb5 0) top left / 60px 51% no-repeat,
    radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) bottom left /60px 51% no-repeat,
    radial-gradient(circle at left top, transparent 10px, #eeeeee 0) top right /240px 51% no-repeat,
    radial-gradient(circle at left bottom, transparent 10px, #eeeeee 0) bottom right /240px 51% no-repeat;
   filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
}

.hollow-compose-many-circles::before {
  content: '';
  height: 80px;
  border: 1px dashed #fff;
  position: absolute;
  left: 60px;
  top: 0;
  bottom: 0;
  margin: auto;
}

.hollow-compose-many-circles::after {
  content: '';
  position: absolute;
  height: 100%;
  width:5px;
  top: 0;
  right: -5px;
  background-image: linear-gradient(to bottom, #eeeeee 5px, transparent 5px, transparent),
  radial-gradient(10px circle at 5px 10px, transparent 5px, #eeeeee 5px);
  background-size: 5px 15px;
}

.hollow-compose-many-circles_left {
  margin-top: 20px;
  width: 300px;
  height: 100px;
  position: relative;
  background: radial-gradient(circle at right top, transparent 10px, #00adb5 0) top left / 60px 51% no-repeat,
    radial-gradient(circle at right bottom, transparent 10px, #00adb5 0) bottom left /60px 51% no-repeat,
    radial-gradient(circle at left top, transparent 10px, #eeeeee 0) top right /240px 51% no-repeat,
    radial-gradient(circle at left bottom, transparent 10px, #eeeeee 0) bottom right /240px 51% no-repeat;
   filter: drop-shadow(2px 2px 2px rgba(0,0,0,.2));
}

.hollow-compose-many-circles_left::before {
  content: '';
  height: 80px;
  border: 1px dashed #fff;
  position: absolute;
  left: 60px;
  top: 0;
  bottom: 0;
  margin: auto;
}

.hollow-compose-many-circles_left::after {
  content: '';
  position: absolute;
  height: 100%;
  width:5px;
  top: 0;
  left: -5px;
  background-image: linear-gradient(to bottom, #00adb5 5px, transparent 5px, transparent),
  radial-gradient(10px circle at 0px 10px, transparent 5px, #00adb5 5px);
  background-size: 5px 15px;
}
</style>
