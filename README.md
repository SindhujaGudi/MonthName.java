# MonthName.java

		class MonthName
		{
			String month_Str;
		public static void main(String[] args)
		{
		MonthName m = new MonthName();
		System.out.println( "Month 1: " + m.month_name(1) );
   		System.out.println( "Month 2: " + m.month_name(2) );
    		System.out.println( "Month 3: " + m.month_name(3) );
    		System.out.println( "Month 4: " + m.month_name(4) );
    		System.out.println( "Month 5: " + m.month_name(5) );
    		System.out.println( "Month 6: " + m.month_name(6) );
    		System.out.println( "Month 7: " + m.month_name(7) );
    		System.out.println( "Month 8: " + m.month_name(8) );
    		System.out.println( "Month 9: " + m.month_name(9) );
	 	System.out.println( "Month 10: " + m.month_name(10) );
    		System.out.println( "Month 11: " + m.month_name(11) );
    		System.out.println( "Month 12: " + m.month_name(12) );
 			System.out.println( "Month 43: " + m.month_name(43) );

	}
	
	String month_name(int i)
	{
		
        	
		switch (i) 
		{
  		          case 1:  month_Str = "January";
                	  break;
  		          case 2:  month_Str = "February";
                	  break;
 		          case 3:  month_Str = "March";
                	  break;
 		          case 4:  month_Str = "April";
                	  break;
		          case 5:  month_Str = "May";
                	  break;
		          case 6:  month_Str = "June";
                	  break;
		          case 7:  month_Str = "July";
                	  break;
		          case 8:  month_Str = "August";
                	  break;
		          case 9:  month_Str = "September";
                	  break;
		          case 10: month_Str = "October";
                	  break;
		          case 11: month_Str = "November";
                	  break;
		          case 12: month_Str = "December";
	        	  break;
		          default: month_Str = "Invalid month";
                     	  break;
        	}
		
		return month_Str;

	}
}
