1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:<script>
        var a = '��';
        var b = '��';
        var c = a.concat(b);
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h1');
        div.innerHTML = c;
    </script>

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:<script>
        var a = '87';
        var b = a.padEnd(6,'0');
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h2');
        div.innerHTML = b;
    </script>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:<script>
        var a = 79387.348;
        var b = a.toFixed(2);
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h3');
        div.innerHTML = b;
    </script>

4.һ��ͼƬ��һ�����·��img/head/,icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:<script>
        var a = 'img/head/icon/1.jpg';
        var b = a.slice(0,-5);
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h4');
        div.innerHTML = b;
    </script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh1��Ԫ����,��ʾ��ҳ��idΪh4��Ԫ����
��:<script>
        var a = prompt('��������֤��:abc');
        if(a.toLowerCase() == 'abc' || a.toUpperCase() == 'ABC'){
            alert('������ȷ');
        }else{
            alert('�������');
        }
        var div = document.createElement('div');
        document.body.appendChild(div);
        div.setAttribute("id",'h5');
        div.innerHTML = a;
    </script>