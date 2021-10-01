# odooext-cybro-OpenHRMS-fix
Some payroll module fixes.
The payroll_account module action_payslip_done method doesn't set tax_line_id on account.move.lines correctly. And it doesn't have good way of being overwritten so 
i'm making a copy of that module with a fixed method.
