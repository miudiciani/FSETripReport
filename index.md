## FSE Trip Report Form Proof of Concept

**Assumptions**

1. This form is a visual concept only, a real implementation of this form would include tethers directly to MSFT Dynamics to the Account Tech Profile  and Account Opportunity solution.
2. TBD update

## START FSE Trip Report

**Customer:**

*This would be an API calls or other connection type to the CRM "Accounts, Account Executives" in the MSFT Dynamics system, probably an Array/DB of objects of each type.*

| Customer  | Account Executive    | Topic                             |
| :--------- | :------------------  | :----                            |
|       <form>
         <select name = "dropdown">
            <option value = "Computer Architecture" selected>Computer Architecture</option>
            <option value = "Java">Java</option>
            <option value = "Discrete Mathematics">Discrete Mathematics</option>
         </select>
      </form>           | API AUTOPOPULATE     | <textarea>Enter Topic</textarea> |
