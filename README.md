ECWF Data Flavor
=======================================
Includes the basic ECMWF software stack, with MARS client and an environment with `ecCodes`, `Metview`, `Earthkit` and `Aviso`.

Getting started
---------------

* Clone or download the code from the source repository.
* Install ansible and other dependencies. You may want to do it in its own virtual environment (`pip install -r requirements.txt`)
* Fetch the external requirements
  ```bash
  $ ansible-galaxy role install -r requirements.yml roles/
  ```

* Define your inventory in `inventory`
* Run the apropriate playbook 

  ```bash
  $ ansible-playbook -i inventory ecmwf-data-flavour.yml
  ```

Author
------------------
ECMWF for the European Weather Cloud

<img src="https://climate.copernicus.eu/sites/default/files/inline-images/ECMWF.png"  width="120px" height="120px"> 

![ewc logo](https://europeanweather.cloud/sites/default/files/images/cloud-data-network-SW-v3.png){width=120px  height=120px}
