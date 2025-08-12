Test Case ID	Title	Preconditions	Steps	Test Data	Expected Result
TC_WD_001	Withdraw amount below minimum	User is logged in with sufficient balance	Enter withdrawal amount and submit	99	Withdrawal rejected with error: 'Minimum withdrawal is $100'
TC_WD_002	Withdraw at minimum limit	User is logged in with sufficient balance	Enter withdrawal amount and submit	100	Withdrawal processed successfully
TC_WD_003	Withdraw above minimum limit	User is logged in with sufficient balance	Enter withdrawal amount and submit	101	Withdrawal processed successfully
TC_WD_004	Withdraw below maximum limit	User is logged in with sufficient balance	Enter withdrawal amount and submit	999	Withdrawal processed successfully
TC_WD_005	Withdraw at maximum limit	User is logged in with sufficient balance	Enter withdrawal amount and submit	1000	Withdrawal processed successfully
TC_WD_006	Withdraw above maximum limit	User is logged in with sufficient balance	Enter withdrawal amount and submit	1001	Withdrawal rejected with error: 'Maximum withdrawal is $1,000'
TC_WD_007	Withdraw with decimal amount	User is logged in with sufficient balance	Enter withdrawal amount and submit	100.50	Withdrawal rejected with error: 'Amount must be in whole dollars'
TC_WD_008	Withdraw with non-numeric input	User is logged in with sufficient balance	Enter withdrawal amount and submit	five hundred	Withdrawal rejected with error: 'Invalid amount format'
TC_WD_009	Withdraw with empty input	User is logged in with sufficient balance	Submit withdrawal form without entering amount		Withdrawal rejected with error: 'Amount is required'
TC_WD_010	Withdraw exceeding balance	User is logged in with insufficient balance	Enter withdrawal amount and submit	500	Withdrawal rejected with error: 'Insufficient funds'
