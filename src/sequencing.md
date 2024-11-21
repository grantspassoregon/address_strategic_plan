# Issue: Out of Sequence Numbering

Affected Addresses: 543-547 NE E ST

Description: This is a straightforward case where the address numbers fail to increase monotonically as distance from the city center increases, going from 545 down to 543, then up to 547 (see Figure 4).
Note that in this case we cannot switch 543 and 545 to resolve the issue because 543 also happens to be a duplicate address.
The reason this is difficult to resolve without the proposed language change is that changing the out-of-sequence value (543) involves also changing a neighboring address that by itself violates no addressing rules.
There being no even numbers between 545 and 547, either one or the other could adopt unit numbers (eg. 545 NE E ST UNITS A & B), or one could change its address number in addition (eg. 543 changing to 547, and the current 547 changing to 549).

![Sequencing E St](./images/address_issues_suffixed_sequencing_e_st.png)
