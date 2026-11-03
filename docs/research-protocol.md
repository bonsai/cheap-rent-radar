# Continuous research protocol

## Search area

大阪市24区。区名が明確でない掲載は候補として保留し、対象内と断定しない。

## Search groups

### Ordinary rentals
- HOME'S
- SUUMO
- at home
- CHINTAI
- Other reputable property portals when relevant

Search both broad Osaka-city queries and ward-specific queries for low-rent apartments/rooms. Search result pages are for discovery; verify every candidate on its detail page.

### Sharehouses
- Oakhouse
- Borderless House
- XROSS HOUSE
- GG House
- Other operators with public listing pages

Separate private rooms and dormitory beds. Verify whether the advertised price includes utilities, internet, and common fees.

## Qualification

`monthly_total = rent + management_fee + common_fee`

- Eligible: all required amounts are explicit and total <= 25,000 JPY.
- Ineligible: all required amounts are explicit and total > 25,000 JPY.
- Unknown: one or more required amounts are missing or ambiguous.

If a source combines management fee and common fee into one explicit amount, record it once. Do not double-count.

## Contract and cost fields

Capture when disclosed:

- Deposit, key money, guarantee deposit
- Shikibiki, cancellation deduction, amortization
- Brokerage fee, guarantor company initial/renewal fee
- Fire insurance, key exchange, cleaning
- Utilities and internet inclusion / extra charges
- Contract type and duration
- Notice period and early termination penalty
- Renewal fee, move-out charges, refund conditions

Unknown means unknown, not none or zero.

## Change detection

Use previous reports as the initial comparison ledger:
- New: detail URL/property not previously reported
- Price drop: same listing's verified comparable monthly total decreased
- Price increase: same listing's verified comparable monthly total increased
- Relisting candidate: similar property or changed URL, not confirmed same unit
- Removed: source page explicitly indicates ended/unavailable or the listing is verifiably gone; inaccessible pages alone are not enough

Report material changes only. Preserve source URLs and check dates.

## Report format

1. Run date (JST)
2. Summary counts: newly found / price reduced / price increased / contract findings / unresolved
3. Ordinary rentals
4. Sharehouses (private rooms, dormitories)
5. Contract and fee observations
6. Search coverage and inaccessible sources
7. Source links and checked date per listing

No candidate should be labelled "under 25,000 yen" unless all required fee components are explicit and the sum is within the cap.
