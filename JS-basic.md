
# Variables in javascript

```Javascript

<script>
	//alert
	
	/*var name='john';
	console.log(name);
	alert('this'+' '+name+' '+'myself');*/
	
	//prompt
	
	/*prompt('enter your lastname'); // prompt
	
	var lastname= prompt('enter your lastname');  // assign prompt value to variable
	console.log(lastname);*/
	
	//opertors
	
	var now, john, mark;
	
	/*now =2018;
	
	john= now + 2;
	
	mark = now -33;
	
	console.log(john);
	console.log(now/10); 
	
	john = 26;
	mark = 23;
	
	var age= mark > john;
	console.log(age); */
	
	
	//typeof opertor
	
	console.log(typeof johnolder);
	console.log(typeof agejohn);
	console.log(typeof 'Mark is older than john'); // string
	console.log(typeof x);   // undefined	
	</script>
	
```

---
# switch in javascript
```Javascript

<script>
		var job = 'teacher';
		switch (job)  // switch is used instead of multiple if else case
			{
			case 'engineer':
			console.log('her job is code' + job);
			break;		
			case 'teacher':
			console.log('her job is teach' + job);
			break;		
			case 'driver':
			console.log('her job is car' + job);
				default:
					console.log(job+ 'doing something else');
			}
		
		var firstname= 'john';
		age = 18;
		 switch(true)
			 {
				 case age<13:
   console.log(firstname + 'is a boy' );
   case age >=13 && age <20:
break;					 
   console.log(firstname + 'is a teenager' );
   case age >=13 && age <20:
break;	
	console.log(firstname + 'is a young man');
	case age >=20 && age < 30:
	default:				 
	console.log(firstname + 'is a young man') 
					 
			 }
		
// condition can written in three fom if else, ternary, switch statement
</script>
---

truthly & falsy
	// falsy value = underfine, null , 0 , '' ,NaN
		// truthy value =  taht are not falsy
		
	/*	var height;
		
		if(height)
			{
				console.log('varaible is defined');
			}
		else
		{
			console.log('variable is undefined');
		}
		
		//result will be undefined, since height is not define 
		
		var height = 0;
		
		if(height || height===0) //height is 0
			{
				console.log{'varaible is defined'}
			}
		  else
		{
			console.log('variable is undefined');
		}
		
		//result is variable is defined   */
		
		
