# Detailed Explanation

## Step 1: Analyze Host Requirements

The network was divided based on the number of required hosts:

* 120 Hosts
* 60 Hosts
* 10 Hosts

## Step 2: Apply VLSM

The largest subnet was allocated first to avoid address wastage.

### Allocations:

* 120 Hosts → /25
* 60 Hosts → /26
* 10 Hosts → /28

## Step 3: Configure Devices

* Added routers, switches, and end devices
* Assigned subnet IP addresses
* Configured router interfaces

## Step 4: Configure Static Routing

Static routes were manually added to routers to enable communication between subnetworks.

## Step 5: Verification

* Ping commands executed successfully
* Packet transfer verified using Simple PDU

## Result

Successful communication was established between all subnetworks.

## Key Concepts

* VLSM
* Subnet Masking
* Static Routing
* IP Address Allocation

## Insight

VLSM improves IP address utilization by allocating address spaces according to actual host requirements.
