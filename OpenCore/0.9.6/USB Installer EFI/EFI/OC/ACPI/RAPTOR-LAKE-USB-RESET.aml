//
// SSDT to reset RHUB devices on XHCI controllers to force hardware querying of ports
//
// WARNING: May conflict with existing SSDT-USB-Reset!  Verify names and paths before
//          merging!
//
DefinitionBlock ("", "SSDT", 2, "CORP", "RHBReset", 0x00001000)
{
    /*
     * Start copying here if you're adding this info to an existing SSDT-USB-Reset!
     */

    External (_SB.PC00.XHCI.RHUB, DeviceObj)

    Scope(_SB.PC00.XHCI.RHUB)
    {
        Method (_STA, 0, NotSerialized)  // _STA: Status
        {
            If (_OSI ("Darwin"))
            {
                Return (Zero)
            }
            Else
            {
                Return (0x0F)
            }
        }
    }

    /*
     * End copying here if you're adding this info to an SSDT-USB-Reset!
     */
}