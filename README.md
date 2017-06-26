# Titanic-Data-Analysis
There have been many cases of extreme disasters in the history of the mankind, but the magnitude of Titan- ic’s disaster ranks as high as the depth it sank to. So it is a way to analyse the losses caused to society.



*****************Output-1******


hduser@Diwakar:~$ hadoop jar /home/diwakar/Desktop/Hadoop/final-jarfiles/Titanic.jar Average_age /Projects/TitanicData.txt /op6<br/>
17/06/26 12:14:07 WARN util.NativeCodeLoader: Unable to load native-hadoop library for your platform... using builtin-java classes where applicable<br/>
17/06/26 12:14:08 INFO Configuration.deprecation: session.id is deprecated. Instead, use dfs.metrics.session-id<br/>
17/06/26 12:14:08 INFO jvm.JvmMetrics: Initializing JVM Metrics with processName=JobTracker, sessionId=<br/>
17/06/26 12:14:08 WARN mapreduce.JobSubmitter: Hadoop command-line option parsing not performed. Implement the Tool interface and execute your application with ToolRunner to remedy this.<br/>
17/06/26 12:14:08 INFO input.FileInputFormat: Total input paths to process : 1<br/>
17/06/26 12:14:08 INFO mapreduce.JobSubmitter: number of splits:1<br/>
17/06/26 12:14:08 INFO mapreduce.JobSubmitter: Submitting tokens for job: job_local1353707139_0001<br/>
17/06/26 12:14:08 INFO mapreduce.Job: The url to track the job: http://localhost:8080/<br/>
17/06/26 12:14:08 INFO mapreduce.Job: Running job: job_local1353707139_0001<br/>
17/06/26 12:14:08 INFO mapred.LocalJobRunner: OutputCommitter set in config null<br/>
17/06/26 12:14:08 INFO mapred.LocalJobRunner: OutputCommitter is org.apache.hadoop.mapreduce.lib.output.FileOutputCommitter<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: Waiting for map tasks<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: Starting task: attempt_local1353707139_0001_m_000000_0<br/>
17/06/26 12:14:09 INFO mapred.Task:  Using ResourceCalculatorProcessTree : [ ]<br/>
17/06/26 12:14:09 INFO mapred.MapTask: Processing split: hdfs://localhost:54310/Projects/TitanicData.txt:0+61111<br/>
17/06/26 12:14:09 INFO mapred.MapTask: (EQUATOR) 0 kvi 26214396(104857584)<br/>
17/06/26 12:14:09 INFO mapred.MapTask: mapreduce.task.io.sort.mb: 100<br/>
17/06/26 12:14:09 INFO mapred.MapTask: soft limit at 83886080<br/>
17/06/26 12:14:09 INFO mapred.MapTask: bufstart = 0; bufvoid = 104857600<br/>
17/06/26 12:14:09 INFO mapred.MapTask: kvstart = 26214396; length = 6553600<br/>
17/06/26 12:14:09 INFO mapred.MapTask: Map output collector class = org.apache.hadoop.mapred.MapTask$MapOutputBuffer<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: <br/>
17/06/26 12:14:09 INFO mapred.MapTask: Starting flush of map output<br/>
17/06/26 12:14:09 INFO mapred.MapTask: Spilling map output<br/>
17/06/26 12:14:09 INFO mapred.MapTask: bufstart = 0; bufend = 8647; bufvoid = 104857600<br/>
17/06/26 12:14:09 INFO mapred.MapTask: kvstart = 26214396(104857584); kvend = 26210836(104843344); length = 3561/6553600<br/>
17/06/26 12:14:09 INFO mapred.MapTask: Finished spill 0<br/>
17/06/26 12:14:09 INFO mapred.Task: Task:attempt_local1353707139_0001_m_000000_0 is done. And is in the process of committing<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: map<br/>
17/06/26 12:14:09 INFO mapred.Task: Task 'attempt_local1353707139_0001_m_000000_0' done.<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: Finishing task: attempt_local1353707139_0001_m_000000_0<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: map task executor complete.<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: Waiting for reduce tasks<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: Starting task: attempt_local1353707139_0001_r_000000_0<br/>
17/06/26 12:14:09 INFO mapred.Task:  Using ResourceCalculatorProcessTree : [ ]<br/>
17/06/26 12:14:09 INFO mapred.ReduceTask: Using ShuffleConsumerPlugin: org.apache.hadoop.mapreduce.task.reduce.Shuffle@ab00d34<br/>
17/06/26 12:14:09 INFO reduce.MergeManagerImpl: MergerManager: memoryLimit=334338464, maxSingleShuffleLimit=83584616, mergeThreshold=220663392, ioSortFactor=10, memToMemMergeOutputsThreshold=10<br/>
17/06/26 12:14:09 INFO reduce.EventFetcher: attempt_local1353707139_0001_r_000000_0 Thread started: EventFetcher for fetching Map Completion Events<br/>
17/06/26 12:14:09 INFO reduce.LocalFetcher: localfetcher#1 about to shuffle output of map attempt_local1353707139_0001_m_000000_0 decomp: 10431 len: 10435 to MEMORY<br/>
17/06/26 12:14:09 INFO reduce.InMemoryMapOutput: Read 10431 bytes from map-output for attempt_local1353707139_0001_m_000000_0<br/>
17/06/26 12:14:09 INFO reduce.MergeManagerImpl: closeInMemoryFile -> map-output of size: 10431, inMemoryMapOutputs.size() -> 1, commitMemory -> 0, usedMemory ->10431<br/>
17/06/26 12:14:09 INFO reduce.EventFetcher: EventFetcher is interrupted.. Returning<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: 1 / 1 copied.<br/>
17/06/26 12:14:09 INFO reduce.MergeManagerImpl: finalMerge called with 1 in-memory map-outputs and 0 on-disk map-outputs<br/>
17/06/26 12:14:09 INFO mapred.Merger: Merging 1 sorted segments<br/>
17/06/26 12:14:09 INFO mapred.Merger: Down to the last merge-pass, with 1 segments left of total size: 10422 bytes<br/>
17/06/26 12:14:09 INFO reduce.MergeManagerImpl: Merged 1 segments, 10431 bytes to disk to satisfy reduce memory limit<br/>
17/06/26 12:14:09 INFO reduce.MergeManagerImpl: Merging 1 files, 10435 bytes from disk<br/>
17/06/26 12:14:09 INFO reduce.MergeManagerImpl: Merging 0 segments, 0 bytes from memory into reduce<br/>
17/06/26 12:14:09 INFO mapred.Merger: Merging 1 sorted segments<br/>
17/06/26 12:14:09 INFO mapred.Merger: Down to the last merge-pass, with 1 segments left of total size: 10422 bytes<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: 1 / 1 copied.<br/>
17/06/26 12:14:09 INFO Configuration.deprecation: mapred.skip.on is deprecated. Instead, use mapreduce.job.skiprecords<br/>
17/06/26 12:14:09 INFO mapred.Task: Task:attempt_local1353707139_0001_r_000000_0 is done. And is in the process of committing<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: 1 / 1 copied.<br/>
17/06/26 12:14:09 INFO mapred.Task: Task attempt_local1353707139_0001_r_000000_0 is allowed to commit now<br/>
17/06/26 12:14:09 INFO output.FileOutputCommitter: Saved output of task 'attempt_local1353707139_0001_r_000000_0' to hdfs://localhost:54310/op6/_temporary/0/task_local1353707139_0001_r_000000<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: reduce > reduce<br/>
17/06/26 12:14:09 INFO mapred.Task: Task 'attempt_local1353707139_0001_r_000000_0' done.<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: Finishing task: attempt_local1353707139_0001_r_000000_0<br/>
17/06/26 12:14:09 INFO mapred.LocalJobRunner: reduce task executor complete.<br/>
17/06/26 12:14:09 INFO mapreduce.Job: Job job_local1353707139_0001 running in uber mode : false<br/>
17/06/26 12:14:09 INFO mapreduce.Job:  map 100% reduce 100%<br/>
17/06/26 12:14:09 INFO mapreduce.Job: Job job_local1353707139_0001 completed successfully<br/>
17/06/26 12:14:09 INFO mapreduce.Job: Counters: 38<br/>
	File System Counters<br/>
		FILE: Number of bytes read=29524<br/>
		FILE: Number of bytes written=543541<br/>
		FILE: Number of read operations=0<br/>
		FILE: Number of large read operations=0<br/>
		FILE: Number of write operations=0<br/>
		HDFS: Number of bytes read=122222<br/>
		HDFS: Number of bytes written=18<br/>
		HDFS: Number of read operations=13<br/>
		HDFS: Number of large read operations=0<br/>
		HDFS: Number of write operations=6<br/>
	Map-Reduce Framework<br/>
		Map input records=891<br/>
		Map output records=891<br/>
		Map output bytes=8647<br/>
		Map output materialized bytes=10435<br/>
		Input split bytes=112<br/>
		Combine input records=0<br/>
		Combine output records=0<br/>
		Reduce input groups=2<br/>
		Reduce shuffle bytes=10435<br/>
		Reduce input records=891<br/>
		Reduce output records=2<br/>
		Spilled Records=1782<br/>
		Shuffled Maps =1<br/>
		Failed Shuffles=0<br/>
		Merged Map outputs=1<br/>
		GC time elapsed (ms)=54<br/>
		CPU time spent (ms)=0<br/>
		Physical memory (bytes) snapshot=0<br/>
		Virtual memory (bytes) snapshot=0<br/>
		Total committed heap usage (bytes)=603979776<br/>
	Shuffle Errors<br/>
		BAD_ID=0<br/>
		CONNECTION=0<br/>
		IO_ERROR=0<br/>
		WRONG_LENGTH=0<br/>
		WRONG_MAP=0<br/>
		WRONG_REDUCE=0<br/>
	File Input Format Counters <br/>
		Bytes Read=61111<br/>
	File Output Format Counters <br/>
		Bytes Written=18<br/>
hduser@Diwakar:~$ <br/>
