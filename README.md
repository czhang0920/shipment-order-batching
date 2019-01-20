# shipment-order-batching
Infer order batches (orders that are loaded and delivered in a specific time window e.g., morning, afternoon)

Input data: large-scale shipment data for two warehouses in 180 days
Objective: uncover the batching patterns of the delivery services; the batch info is useful in understanding the current service level
Assumptions: orders of one batch are loaded and delivered (almost) simultaneously due to the capacity of the delivery truck
