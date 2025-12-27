# Aussie Rentals Business Rules

## Customer Constraints
1. **License Verification:** Every individual listed as a driver (the primary renter and any additional drivers) must present a current, unexpired driver's licence appropriate for the vehicle class.
2. **Blacklist Policy:** A rental application must be refused if the primary renter OR any proposed additional driver appears on the corporate blacklist.
3. **Minimum Age:** All authorized drivers must be at least 18 years of age.
4. **Future Reservations:** A customer may have multiple future reservations, but may have only one car at any time

## Car allocation for advance reservations

At the end of each working day, branches must run the following allocation procedure for all reservations scheduled for pick-up on the following working day.

### 1. Identify Available Inventory
Only cars that meet the following criteria are eligible for allocation:
*   **Location:** The car must be physically present at the specific branch.
*   **Status:** The car must be in an "Available" or "Ready" status (not currently rented, undergoing maintenance, or flagged for cleaning).

### 2. Allocation Priority Sequence
Reservations must be processed in the following order to ensure the most specific requests and highest-value customers are handled first:

1.  **Specific Model Requests:** Process reservations that requested a specific model.
    *   Assign the requested model if available.
    *   If the specific model is unavailable, move to the "Group Upgrade" logic (Step 3).
2.  **Standard Group Requests:** Process reservations that requested a car group (without a specific model).
    *   Assign any available car within the requested group.
3.  **Tie-Breaking (The "Low Usage" Rule):** If multiple eligible cars exist for a single reservation, assign the car with the **lowest total number of historical reservations** to balance wear and tear across the fleet.

### 3. Handling Shortages (Upgrade Logic)
If the requested group or model is unavailable, apply these rules in order:
1.  **Check for "One-Group Free Upgrade":** A car from the next higher group may be assigned at no additional cost.
2.  **Loyalty Priority:** If multiple customers require an upgrade but higher-group inventory is limited, **Loyalty Incentive Scheme** members must be upgraded first.
3.  **Manual Intervention:** If no cars are available in the requested group or the next higher group, the reservation must be flagged for manual review by the Branch Manager.

### 4. Continuity Constraint
*   **Single Car Limit:** A car cannot be allocated to a customer who currently has an active, unreturned rental, regardless of how many future reservations they hold.

### 5. Walk-in Rentals
1.  **Walk-in Rentals:** Walk-in rentals are allowed for customers who have not yet completed their registration process.
2.  **Walk-in Limit:** The end date of the rental must be before any scheduled booking of the assigned car for maintenance or transfer.
3.  **Walk-in Cost:** Walk-in rentals are charged at a fixed rate of $10 per hour.
4.  **Walk-in Car:** If there are several available cars of the model or group requested, the one with the lowest mileage should be allocated.

### 6. Handover of Car to the Customer
After a car has been assigned to a customer,
1. **Driver Age:** Each driver authorized to drive the car during a rental must be over 25 and have held a driver's license for at least one year.
2. **Car Handover:** The car must be returned to the branch at the end of the rental period.
3. **Credit Card:** The customer must provide a credit card number for the duration of the rental.
4. **No Current Rentals:** The driver who signs the rental agreement must not currently have a car on rental.
5. **Credit Card Verification:** Before releasing the car, a credit reservation equivalent to the estimated rental cost must be made against the guaranteeing credit card
6. **Prepare Car:** The car must have been prepared -- cleaned, full tank of fuel, oil and water topped, tires properly inflated, the car must have been prepared – cleaned.full tank of fuel, oil and water topped up.
7. **Roadworthy:** The car must be in good condition and ready for use.



