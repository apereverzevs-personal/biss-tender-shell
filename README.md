# BISS Tender Desk — sign-in page

The public sign-in page for the BISS tender desk. It contains markup, a sign-in
button, the Supabase project URL and the anon key.

Nothing here is sensitive. The anon key is designed to ship in a browser: access
is controlled by row-level security and an allow list in Supabase, not by keeping
this key secret. Tender data, decisions and the rendered desk are private and
live elsewhere.

Built by `build_shell.py` in the private tender-desk repository. Edit it there,
not here.
