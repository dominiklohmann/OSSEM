# Audit Security Group Management

Audit Security Group Management determines whether the operating system generates audit events when specific security group management tasks are performed

This subcategory allows you to audit events generated by changes to security groups such as the following:

* Security group is created, changed, or deleted.
* Member is added or removed from a security group.
* Group type is changed.

[Microsoft Source](https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/audit-security-group-management)

## Data Dictionaries

| EventId | Description | Minimum OS |
|--------|---------|-------|
| [4727](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4727.md) | A security-enabled global group was created. | Windows Vista, Windows Server 2008 |
| [4728](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4728.md) | A member was added to a security-enabled global group. | Windows Vista, Windows Server 2008 |
| [4729](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4729.md) | A member was removed from a security-enabled global group. | Windows Vista, Windows Server 2008 |
| [4730](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4730.md) | A security-enabled global group was deleted. | Windows Vista, Windows Server 2008 |
| [4731](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4731.md) | A security-enabled local group was created | Windows Vista, Windows Server 2008 |
| [4732](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4732.md) | A member was added to a security-enabled local group. | Windows Vista, Windows Server 2008 |
| [4733](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4733.md) | A member was removed from a security-enabled local group. | Windows Vista, Windows Server 2008 |
| [4734](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4734.md) | A security-enabled local group was deleted. | Windows Vista, Windows Server 2008 |
| [4735](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4735.md) | A security-enabled local group was changed. | Windows Vista, Windows Server 2008 |
| [4737](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4737.md) | A security-enabled global group was changed. | Windows Vista, Windows Server 2008 |
| [4754](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4754.md) | A security-enabled universal group was created. | Windows Vista, Windows Server 2008 |
| [4755](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4755.md) | A security-enabled universal group was changed. | Windows Vista, Windows Server 2008 |
| [4756](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4756.md) | A member was added to a security-enabled universal group. | Windows Vista, Windows Server 2008 |
| [4757](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4757.md) | A member was removed from a security-enabled universal group. | Windows Vista, Windows Server 2008 |
| [4758](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4758.md) | A security-enabled universal group was deleted.| Windows Vista, Windows Server 2008 |
| [4764](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4764.md) | A group’s type was changed. | Windows Vista, Windows Server 2008 |
| [4799](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/events/event-4799.md) | A security-enabled local group membership was enumerated. | Windows 10 |