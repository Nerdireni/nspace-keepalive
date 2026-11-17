# nspace-keepalive
Keeps Nspace Supabase backends awake. A GitHub Actions workflow pings each backend's health endpoint every 6 hours, so free Supabase projects never pause from inactivity (Supabase pauses free projects after 7 days with no activity).
Backends watched: nairaspace.com (gieiiofpdgdrsctsrfam, Lovable-managed), Nairaspace Mobile Application (ddhyfpoeznxsbfykobsh), Mindsight Consultation Web Application (pybhnhcdqajymsrskaae). It also pings the live sites.
Note: this keeps awake projects awake. It cannot wake a project that is already paused - resume that once first.
