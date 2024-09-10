# Concepts
* **Reservoirs** have a *capacity* and can contain **Stocks** of a certain amount of a given material at a given point in time
* **Conveyances** have a maximum *rate* and can carry **Flows** at a certain rate of a given material; conveyances can be fixed point-to-point, set routes with multiple ingress and egress, or packet-routed / addressable
* **Transformers** have the ability to *change* input materials to output materials (both products and waste) with a given amount of energy using one or more **Processes**

# Scope of Observation
| Domain | Entity | Type | Notes | Observation Methods |
| --- | --- | --- | --- | --- |
| **Water** | Reservoirs & Dams | Reservoir | Natural, Manmade, Aquifers | GIS, Public Internet |
| | (Atmosphere) | (Reservoir) | |
| | (High-altitude terrain) | (Reservoir) | |
| | (Watersheds) | (Reservoir) | |
| | Water Levels | Stock | | Sensor Networks, Direct |
| | (Humidity) | (Stock) | Atmospheric water vapor |
| | Snow & Ice Levels | Stock | Snowpack, Glaciers | Sensor Networks, Direct |
| | Wells | Conveyance | *from* Aquifers | GIS, Public Internet | 
| | Rivers / Canals / Aqueducts | Conveyance | *from* Watersheds, Reservoirs *to* Reservoirs | GIS |
| | Precipitation | Flow | | API |
| | Waterflow | Flow | inc. Snowmelt | Sensor Networks |
| | Treatment Plants | Transformer | | GIS, Public Internet |
| | Desalination Plants | Transformer | | GIS, Public Internet |
| **Energy** | Power Plants | Transformer | | GIS, Public Internet |
| | Substations | Transformer | | GIS, Public Internet, Direct |
| | Transformers | Transformer | Substation, Distribution | Direct |
| | Capacitor Banks | Transformer | | Direct |
| | Transmission Lines | Conveyance | | GIS, Direct |
| | Distribution Lines | Conveyance | | GIS, Direct |
| | Service Lines | Conveyance | | Direct
| | Energy Storage | Reservoir | Batteries, Pumped Hydro, Thermal | GIS, Direct |
| **General Materials** | Stockpiles | Reservoir | | GIS |
| | Storage Tank | Reservoir | Water, Oil, Other | GIS, Direct |
| | Shipping Containers | Reservoir | | Direct |
| | Warehouses | Reservoir | | GIS, Direct |
| | Distribution Centers | | | | |
| | Inventories | Stock | | ? |
| | Pipelines | Conveyance | Water, Oil, Gas, Mining, Other | GIS, Public Internet |
| | Conveyors | Conveyance | | GIS, Direct |
| | Process Plants | Transformer | | GIS, Public Internet |
| **Minerals** | Mines / Pits / Shafts | Reservoir | | GIS, Public Internet |
| | Reserves | Stock | | Public Internet |
| | Haulers | Conveyance | | ? | 
| | Beneficiation Systems | Transformer | | GIS, Public Internet |
| **Agriculture** | Fields | Reservoir | | GIS |
| | Grain Elevators & Silos | Reservoir | | GIS, Direct |
| | Crops / Herds | Stock | | Direct |
| | Growings | Transformer | | Direct |
| | Harvests | Transformer | | Direct |
| | Packing / Processing Plants | Transformer | | GIS, Public Internet, Direct |
| **Air Transportation** | Aircraft | Conveyance | | Public Internet |
| | Flights | Flow | | 
| | Airports | | |
| | Runways | | | 
| **Marine Transportation** | Oil Tankers | Conveyance | | Private Internet |
| | Bulk Carriers | Conveyance | | Private Internet |
| | LNG Carriers | Conveyance | | Private Internet |
| | Container Ships | Conveyance | | Private Internet |
| | Ship Loaders & Cranes | Conveyance | | GIS |
| | Ship Voyages | Flow | | Private Internet |
| | Ports | | |
| | Terminals | | |
| | Berths | | |
| **Ground Transportation** | Trucks | Conveyance | | Direct |
| | Rail Cars | Conveyance | | Direct |
| | Railway | Conveyance | | GIS |
| | Rail Transit | Flow | | Direct |
| | Container Hauls | Flow | | Direct |
| | Car Dumpers | Flow | | GIS, Public Internet |
