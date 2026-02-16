# Dependencies
In earlier notes you should have covered the principles of high availability with me. If that is not the case, please bring that to my attention now.

The world of telecommunications can be a bit odd! We have vendors who own infrastructure. And we have vendors who offer services across other people's infrastructure. When we're determining which vendors provide diversity, we have to ensure that there are no interdependencies between their networks.

Long ago, many vendors of communication services used the same carrier to provide their services in the northwest. And then one evening, some folks decided to rob a petrol station in Roscommon. Being quite clever (!), they pulled up a manhole cover to cut the phone lines to prevent the burglar alarm from working. 

Oops!

They cut the fibre bundle that was providing services to the northwest of the country. Every independent provider who was using that fibre optic service for back haul, lost connectivity simultaneously. Despite having two independent carriers connecting to their business, both independent connections went down simultaneously and the businesses lost their connectivity.

It is not enough to provide services from two independent carriers. We must identify the infrastructure used and determine that there is in fact diversity. In many places in Ireland there may in fact be only two terrestrial infrastructures. Letterkenny may be a bit unique, as we had

- Eir, like everywhere else in the country
- ESBT/E-Net, like almost everywhere else in the country
- A BT fibre from Derry
- Project Kelvin

A locally owned Microwave network was operated by [NWEWN](https://www.bluebox.network/) 



