## Problems Encountered

### DNS Resolution Issue

Symptoms:

- `ping server01` failed
- `ping server01.lab.local` worked
- Domain join failed
    ![Domain join failure](../screenshots/img7.png)
Investigation:

- Ran `ipconfig /all`
- Used `nslookup`
- Found provider DNS suffix interference
    ![DNS suffix interference](../screenshots/img8.png)
Resolution:

- Removed incorrect DNS configuration
    ![nslookup returns expected results](../screenshots/img10.png)
## Lessons Learned

- DNS is often the root cause of domain join failures
- FQDN behavior can reveal suffix issues
- Always validate client DNS configuration first
