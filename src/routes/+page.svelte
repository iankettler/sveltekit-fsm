<script>
	import { Company } from '$lib/enum/company.ts'
	import { companyDB } from '$lib/db/company.json'

	const companies: Company[] = JSON.stringify(companyDB)

	console.log(companies)
</script>
