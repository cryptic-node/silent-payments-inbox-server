# silent-payments-inbox-server
Silent Payments “inbox” server. Silent Payments (BIP-352) let someone send you Bitcoin to a reusable static address without address reuse.  A Rust service that scans blocks for your silent payment outputs, notifies you (Nostr DM, ntfy, email), and shows a dashboard of incoming payments
