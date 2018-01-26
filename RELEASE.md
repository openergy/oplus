# oplus

**(M): major, (m): minor, (p): patch**

### 5.0.0
* (m): EIO logger name argument
* (M): EPWHeader, removed:
    - start day of week
    - get field
    - set field
* (m): EPW logger name
* (p): sort_df to account for pandas backward compatibilities
* (p): debug double space in eplusout.err strings
* (p): in parsing *.err file, debug the case when "\******* Beginnning" is
never encountered
* (m): IDD loggers
* (m): MTD logger name
* (m): OutputTable logger name
* (p): simulation debug read_only epw files when copied
* (p): linux compatibility for EnergyPlus 8.6.0
* (M): pandas sort_index instead of deprecated sort
* (m): report_key management in SummaryTable.get_table_df
* (p): redirect stream debug
* (p): run_subprocess encoding

### 4.6.0
* (m): idf styles added
* (m): epw header completed
* (p): err debug
* (m): simulation beat_freq implemented
* (p): subprocess management enhanced

### 4.5.1
* **(p) conda-requirements.txt added, setup.py enhanced**

### 4.5.0
* **(p)simulation.py**:
    * debug: simulate failed to return Simulation object if simulation_name was not none. Corrected.
    * debug: osx summary table file name was wrong
* **(m) idf.py**: new filter condition added : 'in', debug of filter with no condition

### 4.4.3
* corrected PyPi hosting issues

### 4.4.2
* implemented continuous integration

### 4.4.1
* simulation debug: simulate failed to return Simulation object if simulation_name was not none. Corrected.

### 4.4.0
* simulation api changed
* summary table object implemented
* err object implemented
* can create idf and epw from path, content or buffer
* can copy idf

### 4.3.0
* new cache system
* new configuration system
* CONF functions changed

