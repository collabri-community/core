---
search:
  boost: 1.0
---


# Subset: SowSpec 


_Fields populated at SOW specification time. Execution-only fields (lead_org, leads, percent_complete, performance_status, etc.) are optional in this profile._



<div data-search-exclude markdown="1">

URI: [SowSpec](SowSpec.md)








## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/collabri/core











































        

        


        



        


        

        




        

        


        

        




        

        

        





        

        

        



        

        




        


        

        


        


        

        

        

        

        



        



        

        

        

        

        

        

        

        

        

        

        

        

        

        

        


        

        

        



        

        

        


        

        

        

        



        

        


        

        

        

        

        



        

        

        

        

        

        

        

        


        


        


        

        


        

        

        

        


        

        

        




















## Slots in subset

| Slot | Description |
| --- | --- |
| [acceptance_criteria](acceptance_criteria.md) | The condition(s) that must be met for this deliverable to be accepted |
| [accounting_date](accounting_date.md) | The accounting period this entry pertains to — i |
| [action](action.md) | ODRL action term or local action label (e |
| [affiliation](affiliation.md) | The organization this person belongs to |
| [agent](agent.md) | The Organization or Person playing the party role |
| [amount](amount.md) | The amount, with currency |
| [assignee](assignee.md) | Party bound by the obligation |
| [assigner](assigner.md) | Party imposing the obligation |
| [authored_by](authored_by.md) | Author(s) of this version snapshot |
| [award_id](award_id.md) | Sponsor award or contract identifier |
| [budget_entries](budget_entries.md) | Contract-level datestamped budget snapshots |
| [cadence](cadence.md) | Reporting cadence (e |
| [category](category.md) | Discriminator naming the concrete Deliverable subclass for this instance |
| [contract_value](contract_value.md) | Headline contract value for convenience |
| [contracting_parties](contracting_parties.md) | All parties to the contract with their roles |
| [contractual_status](contractual_status.md) | Where this element sits in the contract lifecycle |
| [cost_basis](cost_basis.md) | Headline cost basis for this Payment (fixed_price, cost_reimbursable, etc |
| [created_on](created_on.md) | Date this version snapshot was created |
| [deliverables](deliverables.md) | Deliverables produced by this subtask |
| [depends_on](depends_on.md) | Other subtasks that must complete before this one can proceed |
| [description](description.md) | Narrative description |
| [due_month](due_month.md) | Due date expressed as a whole number of months since program start (month 1 =... |
| [end_date](end_date.md) | Calendar end date of this task (optional; otherwise derived from subtasks) |
| [entry_type](entry_type.md) | Which budget view this entry represents |
| [first_due](first_due.md) | First due-month for the recurring report |
| [format](format.md) | Delivery format (PDF, repository, briefing, etc |
| [id](id.md) | Stable identifier; together with version forms the element IRI |
| [location](location.md) | Location (physical or virtual) of the activity |
| [metric_text](metric_text.md) | Free-text fallback carrying the metric's verbatim statement from the source S... |
| [metrics](metrics.md) | The metric(s) by which this deliverable is evaluated |
| [milestone](milestone.md) | Milestone whose acceptance gates contractual events (e |
| [milestone_type](milestone_type.md) | Kind of milestone event |
| [milestones](milestones.md) | Milestones defined at the SOW level (referenced by subtasks) |
| [name](name.md) | Human-readable name |
| [narrative_type](narrative_type.md) | Subtype of narrative document |
| [notes](notes.md) | Optional free-text notes (e |
| [objective](objective.md) | The aim of this subtask — what success looks like, expressed once, independen... |
| [obligation_class](obligation_class.md) | Discriminator for the concrete Obligation subclass |
| [obligations](obligations.md) | Non-payment obligations attached at the SOW level (reporting cadence, data-sh... |
| [orcid](orcid.md) | ORCID identifier |
| [org_type](org_type.md) | The organization's role in the program |
| [organization](organization.md) | Specific organization this entry breaks out, on multi-org payable subtasks |
| [organizations](organizations.md) | All organizations participating in the SOW |
| [payable_by](payable_by.md) | Which parties owe payment on acceptance of the milestone gating this subtask |
| [payment](payment.md) | Optional payment obligation triggered by milestone acceptance |
| [payor](payor.md) | Which party owes the payable on milestone acceptance |
| [period_of_performance_start](period_of_performance_start.md) | Calendar date on which program month 1 begins |
| [persons](persons.md) | All people referenced anywhere in the SOW |
| [planned_amount](planned_amount.md) | Headline planned payment amount on milestone acceptance |
| [prime](prime.md) | Prime contractor under this contract |
| [program_type](program_type.md) | Funding mechanism for the contract |
| [proposal](proposal.md) | Foreign key to the upstream Proposal Intent record this contract derives from... |
| [proposal_segment](proposal_segment.md) | Identifier of the slice of the upstream proposal this TaskTeam realizes |
| [protocol_url](protocol_url.md) | URL where the method/protocol is documented |
| [rationale](rationale.md) | Why this criterion was chosen |
| [reporting_required](reporting_required.md) | True iff this entry exists to satisfy a contractually-required reporting obli... |
| [repository_url](repository_url.md) | URL of the source repository |
| [revision_label](revision_label.md) | Optional human label for this snapshot (e |
| [role](role.md) | Contract role (sponsor, prime, subcontractor, performer, etc |
| [ror_id](ror_id.md) | ROR identifier for the organization, if available |
| [software_license](software_license.md) | License under which the software is distributed |
| [source_ref](source_ref.md) | Pointer to the document or accounting record this entry derives from — a Chan... |
| [spans_full_award](spans_full_award.md) | True if the task spans the entire period of performance |
| [sponsor](sponsor.md) | Sponsor under this contract |
| [standard_body](standard_body.md) | Organization stewarding the standard, if external |
| [standard_subtype](standard_subtype.md) | Kind of standard (ADMS-aligned) |
| [start_date](start_date.md) | Calendar start date of this task (optional; otherwise derived from subtasks) |
| [statement](statement.md) | The objective expressed as a single, declarative aim |
| [subtasks](subtasks.md) | Subtasks belonging to this task |
| [target_date](target_date.md) | Target calendar date for this milestone |
| [target_month](target_month.md) | Target month (since program start) for this milestone |
| [target_value](target_value.md) | The target value to be achieved |
| [tasks](tasks.md) | Tasks (thematic buckets) that make up this SOW |
| [template_uri](template_uri.md) | Pointer to the required reporting template, if any |
| [terms_ref](terms_ref.md) | Pointer to the governing contract clause |
| [unit](unit.md) | Unit of measure for the target and actual values |
| [verification_method](verification_method.md) | How the criterion will be checked (e |
| [version](version.md) | Semantic version of this element |
| [version_date](version_date.md) | The date this entry was recorded / reported out |




</div>