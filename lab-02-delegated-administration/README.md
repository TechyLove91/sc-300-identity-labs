# Lab 02 – Delegated Administration with Administrative Units (Live Tenant)

## Objective
Implement least-privilege administrative access by creating a restricted Administrative Unit (AU) and assigning a scoped User Administrator role to a regional administrator in Microsoft Entra ID.

This lab demonstrates identity governance concepts used to limit administrative blast radius while enabling regional user management.

---

## Environment
- Identity Platform: Microsoft Entra ID
- Tenant: TechyLove91Labs.onmicrosoft.com
- Administrative Unit: NY-AdminUnit-Lab
- Management Mode: Restricted
- Role Assigned: User Administrator (Scoped)

---

## Lab Accounts (Lab-Only)
**Standard Users**
- Nasir J. (NY Lab User)
- Sean C. (NY Lab User)

**Scoped Administrator**
- NY Regional Admin (Lab)

All accounts were created exclusively for IAM lab testing and governance validation.

---

## Tasks Completed
- Created a restricted Administrative Unit for New York
- Added region-scoped lab users to the Administrative Unit
- Assigned the User Administrator role scoped to the Administrative Unit
- Validated that administrative permissions were limited to AU members only

---

## Evidence (Live Tenant Implementation)

### Administrative Unit Creation
![NY Administrative Unit](screenshots/ny-adminunit-review.png)

### Administrative Unit Membership
![NY AU Users](screenshots/ny-au-users.png)

### Scoped Role Assignment
![Scoped User Administrator Assignment](https://github.com/TechyLove91/sc-300-identity-labs/blob/main/lab-02-delegated-administration/UserAdminRoleScopedtoAU.png?raw=true)

---

## Key Concepts Demonstrated
- Administrative Units (AUs)
- Role-Based Access Control (RBAC)
- Least-privilege administration
- Scoped administrative permissions
- Identity governance and access segmentation

---

## Skills Demonstrated
- Microsoft Entra ID administration
- Secure role assignment and delegation
- Identity governance design
- Administrative scope validation
- Professional IAM lab documentation

---

## Lessons Learned
- Administrative Units effectively restrict administrative visibility and control
- Scoped role assignments significantly reduce security risk
- Proper identity segmentation improves operational security and manageability

---

## Next Steps
- Apply Conditional Access policies scoped to Administrative Units
- Enforce Multi-Factor Authentication (MFA) for privileged roles
- Extend governance controls to additional regions or departments
