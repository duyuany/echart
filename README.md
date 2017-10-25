## 配置项
1. 标题组件，包含主标题和副标题。
  
        title:{
            show： true, //是否显示标题组件
            text: '标题',  //主标题文本，支持使用 \n 换行
            link: '链接', //主标题文本超链接
            target: 'self/blank', //指定窗口打开主标题超链接
            textStyle: {
                color: '#fff', //主标题文字的颜色
                fontStyle: 'normal'/'italic'/'oblique', //主标题文字字体的风格
                fontWeight: 'normal'/'bold'/'bolder'/'lighter'/100 | 200 | 300 | 400..., //主标题文字字体的粗细
                fontFamily: 'serif' , 'monospace', 'Arial', 'Courier New', 'Microsoft YaHei', ..., //主标题文字的字体系列
                fontSize: 18, //主标题文字的字体大小
                align: 'left'/'center'/'right', //文字水平对齐方式
                verticalAlign: 'top'/'middle'/bottom', //文字垂直对齐方式
                lineHeight: 56, //行高
                width: 18/'18%', //文字块的宽度，注意，文字块的 width 和 height指定的是内容高宽，不包含 padding。如果不定义 rich 属性，则不能指定 width 和 height。
                height: 18/'18%',
                textBorderColor: '#000', //文字本身的描边颜色
                textBorderWidth: 1, //文字本身的描边宽度
                textShadowColor: '#000', //文字本身的阴影颜色
                textShadowBlur: 5, //文字本身的阴影长度
                textShadowOffsetX: 10, //文字本身的阴影X偏移
            }
        }
