This repository includes the infrastructure to add detailed logging to turbo integrator (ti) extraction, transformation and loading (etl) solutions.

Steps To Implement
* Pull these objects from the public repository into your environment
* Review the Log.Process.Sample TI
     * Add the header section to the top of your prolog tab where you want logging 
     * Add the footer section to the top of the epilog tab
     * Add error handling logic to calculate intersections added, changed, skipped and deleted
     * Add error handling logic to set status and statusmessage

* Please feel free to fork this and make it better
