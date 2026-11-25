Incident: ACPI service failure simulation and recovery

Objective:
Simulate a service failure, verify the failure state, restart the service, and confirm successful recovery.

Incident Timeline

1. Initial State
   
   - The "acpid.service" service was verified to be running.
   - Status: Active

2. Failure Simulation
   
   - The "acpid.service" was stopped to simulate a service failure.
   - The service was subsequently verified as inactive, confirming the failure condition.

3. Recovery Action
   
   - The "acpid.service" was restarted using the system service manager.
   - The restart command completed successfully.

4. Recovery Verification
   
   - The service status was checked again after the restart.
   - Status: Active
   - This confirmed that the service successfully recovered from the simulated failure.

Result

The manual chaos test was completed successfully. The service failure was simulated, the inactive state was observed, and the service was restarted and verified to be active again.

Final Status: Recovered successfully.
