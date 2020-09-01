TECHTREE ENTRIES
grcloak-scout.odf		0							// Romulan scout cloak
grcloak-cargo.odf		2	rbase.odf rompod9.odf	// Romulan cargo ship phase cloak
grcloak-turret.odf		1	rompod16.odf			// Romulan turret cloak
gccloak-scout.odf		0					// Cardassian scout cloak
gccloak-cargo.odf		1	cbase.odf		// Cardassian cargo ship cloak
gkcloak-cargo.odf		1	kbase.odf		// Klingon cargo ship cloak

BUTTON ENTRIES
# Custom cloaks
@reference=64
@tmaterial=interface
b_grcloak-scout			gbcloak00		0	0	64	64
b_grcloak-cargo			gbcloak00		0	0	64	64
b_grcloak-turret		gbcloak00		0	0	64	64
b_gccloak-scout			gbcloak00		0	0	64	64
b_gccloak-cargo			gbcloak00		0	0	64	64
b_gkcloak-cargo			gbcloak00		0	0	64	64

HOTKEY ENTRIES
##### Romulan Special Weapons
# Romulan Scout Cloak
wc_grcloak-scout {
	+ keyboard	BackQuote
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}
# Romulan Cargo Ship Phase Cloak
wc_grcloak-cargo {
	+ keyboard	BackQuote
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}
# Romulan Turret Cloak
wc_grcloak-turret {
	+ keyboard	BackQuote
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}

##### Cardassian Special Weapons
# Cardassian Scout Cloak
wc_gccloak-scout {
	+ keyboard	BackQuote
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}
# Cardassian Cargo Ship Cloak
wc_gccloak-cargo {
	+ keyboard	BackQuote
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}

##### Klingon Special Weapons
# Klingon Cargo Ship Cloak
wc_gkcloak-cargo {
	+ keyboard	BackQuote
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}

EXTRA TECHTREE ENTRIES IF USING XML - EITHER/OR DEPENDENCIES
grcloak-cargo.odf		2	rtrading.odf rompod9.odf	// Romulan cargo ship phase cloak
gccloak-cargo.odf		1	ctrading.odf				// Cardassian cargo ship cloak
gkcloak-cargo.odf		1	ktrading.odf				// Klingon cargo ship cloak
