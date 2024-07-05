The CWRU dataset, provided by Case Western Reserve University, is a popular open-source dataset that is easily accessible and widely used. It is known as the standard reference dataset for testing the performance of various machine learning (ML) and deep learning (DL) algorithms. The dataset contains information on Normal Bearing, Single Point Drive-End (DE), and Fan-End (FE) defects.

The data was collected using an experimental setup that involved a CWRU bearing test rig with a 2 hp Reliance electric induction motor, a torque transducer, a dynamometer, and control electronics. The dataset consists of 161 records divided into four classes:
48k normal-baseline

48k drive-end fault

12k drive-end fault

12k fan-end fault

Each class further includes datasets for different fault types such as Ball bearing (B) fault, Inner-race fault, and Outer-race faults categorized based on location relative to the load zone: 'Centered,' 'Orthogonal,' and 'Opposite'.

To induce faults, electro-discharge machining was used with specific diameters ranging from 7 mils to 40 mils. The data collection involved two sampling frequencies: 12 kHz and 48 kHz, capturing vibration data for motor loads ranging from 0 to 3 horsepower and motor speeds from 1720 to 1797 RPM.

The data files are saved in MATLAB (.mat) format with filenames indicating fault positions, diameters, and bearing loads. For example, 'B007_0' represents ball bearing fault data with a 0.007-inch diameter and no load, while 'OR014@6_1' includes outer-race fault data with a 0.014-inch diameter, positioned at the center, and operated under a 1 horsepower load.
