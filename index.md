# FSE Trip Report Form Proof of Concept

**Assumptions**

1. This form is a visual concept only, a real implementation of this form would include tethers directly to MSFT Dynamics to the Account Tech Profile  and Account Opportunity solution.
2. TBD update

## FSE Trip Report

**Customer:**

*This would be an API calls or other connection type to the CRM "Accounts, Account Executives" in the MSFT Dynamics system, probably an Array/DB of objects of each type.*

Customers | Account Executives
----------| ------------------
<form method="post">
	<select name="Customers">
		<option value="Callahan Auto">Callahan Auto</option>
		<option value="Prestige Worldwide">Prestige Worldwide</option>
		<option value="Cyberdyne">Cyberdyne</option>
	</select>
</form> | <form method="post">
      <select name="Account Executive">
        <option value="Angelina Jolie">Angelina Jolie</option>
        <option value="Lake Bell">Lake Bell</option>
        <option value="Emily Ratajkowski">Emily Ratajkowski</option>
      </select>
    </form>
