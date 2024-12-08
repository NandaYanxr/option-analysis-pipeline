# For_PrismFP
#coding_test_of_option
Hiiiii,
Please see and run main_py file for my code and result.

Where I assume input in format:

  -target_instrument_id = ["id1", "id2",...](list,length=dynamic,type=string)
  -target_period = [start_time, end_time](list,length=2,timestamp format = %H:%M:%S:%f",start_time<=timestamp<=end_time)
  -target_static_fields = ["field1", "field2",...](list,length=dynamic,type=string)
  -target_dynamic_fields = ["field1","field2",...](list,length=dynamic,type=string)
  
Output is a pd format table:
  -instrument_id|start_time|end_time|field1|field2|...(Static)|field1|field2...(Dynamic)
  -each row represents an instrument_id
      -each cell is All Unrepeated Values Set ever shown during target_period
      -"N/A" means some instrument_id doesn't have the specific target_fields record during target_period

If any promblems,don't hesitate to let me know! 
Thank you and looking forward to future process.

Best,
Xinru Yan
