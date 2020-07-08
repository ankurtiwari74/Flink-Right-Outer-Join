# Flink-Right-Outer-Join

Command I used to demonstrate Right Outer Join in Flink:

/home/ankur/Flink/flink-1.10.1/bin/flink run -c rightOuterJoinPackage.RightOuterJoin /home/ankur/Flink-Execution//Jars/rightOuterJoin.jar --input1 file:///home/ankur/Flink-Execution/Inputs/personInnerJoin.txt --input2 file:///home/ankur/Flink-Execution/Inputs/locationInnerJoin.txt --output file:///home/ankur/Flink-Execution/Outputs/rightOuterJoin/ROJ

path_for_flink run -c package_name.class_name --input1 path_of_1st_input --input2 path_of_2nd_input --output path_to_output_location
