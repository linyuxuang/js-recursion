# js-recursion
js 递归

  js 递归如下例子 一看就明白（递归的规律先执行的最后才执行完，等最底下的返回之后才一层一层的往回靠）
   注意  两点 1：找规律    2：找让递归停止的条件
  
      function recursion(n){
        	if(n==1){
        		return 1
        	}
        		return n*recursion(n-1)   // 7*6*5*4*3*2*1=5040

        }
	  	console.log(dg(7))   //5040


        function recursion(n){
        	if(n==1){
        		return 1
        	}
        		return n+recursion(n-1)   // 7+6+5+4+3+2+1=28

        }
	  	 console.log(dg(7))   //28





