#第五章 JavaScript语句

5.1.1 if语句

		var a = 10;
        //小括号里一定要是true
        if(a<20){
            alert('yes');
        }
5.1.2 if...else语句

		if(a<10){
            alert('yes');
        }else{
            alert('no');
        }
5.1.3 if...else if语句

		if(a<60){
            alert('D');
        }else if(a>=60 && a<75){
            alert('C');
        }else if(a>=75 && a<85){
            alert('B');
        }else if(a>=85 && a<=100){
            alert('A');
        }else{
            alert('缺考');
        }
5.1.4 switch语句

switch小括号中一般情况是一个变量名,这个变量可能会有不同的取值.所有的case都是"或"的关系,case后面的值会与变量值做比对,满足后就执行case后面的代码.不写break就会将所有的比对进行一遍.

		var a = 10;
        switch(){
            case 值1:
            //执行代码
            break;
            case 值2:
            //执行代码
            break;
            case 值3:
            //执行代码
            break;
            case 值n:
            //执行代码
            break;
            default:
            //执行代码
        }
###5.2 循环语句
5.2.1 while循环

while语句是一种前测试语句（先判断以下在执行），循环的目的是为了反复执行语句或代码块，只要表达式为true就继续循环，一旦为假的时候，循环退出.

		var a = 10;
        while(a<15){
            //10
            //11
            //12
            //13
            //14
            alert('你好');
            a++;
            //11
            //12
            //13
            //14
            //15
        }
5.2.2 do...while语句

do...while语句是一种后测试语句,就是在循环体中的代码执行之后,才开始判断条件.也就是说,在表达式判断之前,循环体内的代码至少会被执行一次.

		var a = 0;
        do{
            alert('你好');
            a++;
        }while(a<5);
5.2.3 for循环

for语句是一种前测试语句,一般情况下,有三个基础表达式语句,每一个要用分号隔开.

		//  初始化    判断 更新
		for(var x = 0;x<y;x++){
			//执行循环体
            alert(x);
        }
		//顺序为:初始化-->判断-->执行循环体-->更新