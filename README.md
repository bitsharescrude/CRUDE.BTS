# CRUDE.BTS
The Smartcoin version of CRUDE.NGN
#DESCRIPTION
This Asset follows the daily price of bitshares in Naira and is backed by CRUDE.NGN, it represents the value of 1BTS.

# SMARTCOIN Parameters
- Current Supply 2,000.00000
- Max Supply 3,600,570,503.00000
- Stealth Supply 0
- Precision 5(0.00001)
- Market Fee Rate 0.1%
- Market Fee Referral Reward 10%
- Max Market Fee 10,000,000,000.00000
- Core Exchange Rate(CER) 2.00000 CRUDE.BTS / BTS

# Permissions
- Enable market fee
- Require holders to be white-listed
- Issuer may transfer asset back to himself
- Issuer must approve all transfers
- Disable force settling
- Allow issuer to force a global settling
- Disable confidential transactions
- Allow witnesses to provide feeds
- Allow committee members to provide feeds
# Flags
- Enable market fee

# Settlement
- Force settlement delay(hours) 1.0
- Max. settlement each period (100.0%)

- Backing asset CRUDE.NGN
- Feed lifetime (hours) 144.0
- Minimum feeds 1
- Maintenance collateral ratio (MCR) 1.5
- Maximum short squeeze ratio (MSSR) 1.25

# CRUDE.BTS Protocol
HTLC, Private memo and merchant
# Asset class
 Private Bitasset, Non-Custodial, margin cryptocurrency
# Account Authority
vnc7
# Market Restrictions
(N/B other tradeable assets may be owned by fraudsters trade with caution)

# HOW IT WORKS
Each BitAsset has a feed that is provided by the witnesses that indicate a fair price for that asset.
This so called Settlement Price or Feed Price is used to margin call positions that borrowed BitAssets and can no longer maintain the minimum collateral ratio (i.e. maintenance collateral ratio).
The collateral of these positions is used to buy back the debt from the market automatically and the position will be closed.
By these rules, the network enforces the exchange participants to always maintain a collateral that is higher than the minimum requirement.
Currently, the minimum required collateral ratio is 150% but can be changed by the witnesses.
