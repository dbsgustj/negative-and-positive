# negative-and-positive
Scanner sc = new Scanner(System.in);
		System.out.println("숫자를 입력하세요");
		int n = sc.nextInt();
		
		if(n>0)
			System.out.println("숫자 "+n+"은 양수 입니다.");
		else if(n<0)
			System.out.println("숫자 "+n+"은 음수 입니다.");
		else 
			System.out.println("숫자 "+n+"은 영 입니다.");
