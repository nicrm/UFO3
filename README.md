								BENCHMARKING

1. Formulate a hypothesis/problem statement about behavior of ping times of these three servers:

  	The reason some of the ping times are longer than others is most likely due to the range from where we ping them from are, so the
	farther away the the server we ping is, the longer it will take.

2. Plan an experiment, which measures response times of these three servers:

	I will ping each server 10 times to see if there are any discrepancies or outliers when we ping it.

3. Execute the experiment, which measures response times of these three servers:

	Pinging 128.199.144.199 with 32 bytes of data:
	Reply from 128.199.144.199: bytes=32 time=216ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=207ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=211ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=195ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=196ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=195ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=222ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=211ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=224ms TTL=51
	Reply from 128.199.144.199: bytes=32 time=212ms TTL=51
	For 128.199.144.199 the average time it took was 208ms, while the maximum was 224ms and the minimum was 195ms.
	
	Pinging 167.99.51.33 with 32 bytes of data:
	Reply from 167.99.51.33: bytes=32 time=106ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=92ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=92ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=92ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=93ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=105ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=92ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=110ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=92ms TTL=53
	Reply from 167.99.51.33: bytes=32 time=101ms TTL=53
	For 167.99.51.33 the average time it took was 97ms, while the maximum was 110ms and the minimum was 92ms.
	
	Pinging 46.101.253.149 with 32 bytes of data:
	Reply from 46.101.253.149: bytes=32 time=24ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=22ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=27ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=38ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=17ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=20ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=34ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=20ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=20ms TTL=56
	Reply from 46.101.253.149: bytes=32 time=39ms TTL=56
	For 46.101.253.149 the average time it took was 26ms, while the maximum was 39ms and the minimum was 17ms.

4. Evaluate your experiment and interpret the measurements and results.

	From what i can tell my assumption was correct, that the longer away the servers are the longer the ping times would take, as the first
	one which took the longes 128.199.144.199, was in Singapore. The next one was 167.99.51.33 which was based in the US in New Jersey
	The last one was based in Frankfurt, Germany and took the least time to ping.

