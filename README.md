##Diel-light-pi activity detector
Creates activity detector scripts for the Rasberry pi to monitor diel activity of small insects
##Setup
1. Clone the git repository to your rasberry pi using git clone or download the files.  
2. Run `python3 run_diel-light.py --time` to update time if required.  
3. Run `python3 run_diel-light.py --project` to display output parameters for project.   
4. If they require updating. Modify the `configs/project.conf`  
5.Run `python3 run_diel-light.py --run`

##Modify config files 
Project config files : configs/project.conf.  
Motion tracking config files : configs/motion.conf  
For a more detailed guide on modifying motion tracking parameters, refer to https://motion-project.github.io/
