# TODO

- /Drahtbiegen/Zug/test.py

- Logging

- cleanup python calls

- Yet there is a matplotlib problem to be solved, but that is another piece of cake...

- User shouldn't spent time for installing dependencies. Add binaries for Linux and Windows: ccx, cgx, ng_vol.

- Equalize Python version in all scripts. Now run_all.py uses v.3.

- When the automatic test procedures become more complex (e.g. if they include file comparison) then it might be a good idea to have some sort of lib or helper script in order to not have the same functions defined at multiple locations in the example collection.

- Currently, the test is just a test of being able to run the examples rather than to check for unexpected changes due to new versions of ccx/cgx or modified helper scripts. I already introduced the Refs subdirectories, where results have to go. The intention was to have some other directory which is the 'real' reference for comparison with the results of the current test run. This would imply comparison of images and text files. Yet I didn't take the time to implement this.

- BTW, do you see a simple way of making the monitor.py script really monitoring a running job with automatic update of the convergence plots?