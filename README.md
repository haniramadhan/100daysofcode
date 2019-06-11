# 100daysofcode
My journey to try to document all my codes (learning, tutorial, etc) of 100 days starting ~~2019.05.27~~ 2018.06.11

Current work:
* 2018.06.11 (Class Final Project - Big Data Storage System) Trying to modify the indexing of DITA https://github.com/TsinghuaDatabaseGroup/DITA using machine learning based index. Configured it until fully working in Windows. What I have done:
	1. Using the steps similar to in the readme of DITA github.
	2. Added and configured hadoop in Windows using http://www.barik.net/archive/2015/01/19/172716/
	3. Configured running application in Scala. Link to how to do it: [Click](logs/ConfigureDITAScala.md).
    **What I have learned:**
    	1. Checks about the result of the trajectory similarity (only)
    	2. Executing the SQLExample:
    		*  Still not familiar with how does Spark SQL work.
    		*  Still not familiar how does the trajectory parsed into the SQL query
    	3. Executing the DataFrameExample:
    		+  Have just known that we can examine the result by writing into JSON
    		+  Parsed Trie index to JSON and the result is nonsense: {"index":"(Some(traj1), traj1_index)"}
    	4. Executing the IndexExample:
    		+ Still have no idea, similar to SQLExample.
    * What will I do next?
    	- Try to examine one by one of the line in the DataFrameExample (since I can only check this one intuitively)
    	- Ask my teammate to study about Spark SQL

