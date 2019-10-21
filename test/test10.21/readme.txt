1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:<script>
        var a = '你';
        var b = '好';
        var c = a.concat(b);
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h1');
        div.innerHTML = c;
    </script>

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:<script>
        var a = '87';
        var b = a.padEnd(6,'0');
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h2');
        div.innerHTML = b;
    </script>

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:<script>
        var a = 79387.348;
        var b = a.toFixed(2);
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h3');
        div.innerHTML = b;
    </script>

4.一张图片是一个相对路径img/head/,icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:<script>
        var a = 'img/head/icon/1.jpg';
        var b = a.slice(0,-5);
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h4');
        div.innerHTML = b;
    </script>

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h4的元素中
答:<script>
        var a = prompt('请输入验证码:abc');
        if(a.toLowerCase() == 'abc' || a.toUpperCase() == 'ABC'){
            alert('输入正确');
        }else{
            alert('输入错误');
        }
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h5');
        div.innerHTML = a;
    </script>