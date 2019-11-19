# CVE_Assessments_10_2019

Audacity for Windows Version 2.3.2

Source: https://www.audacityteam.org/download/



The initial identification of the DLL Hijacking vulnerability in the Audacity version 2.1.2 was identified as well in the recent version 2.3.2.  



Reference:

CVE-2017-1000010

https://www.cvedetails.com/cve/CVE-2017-1000010/



[*] Siofra version 1.13 has entered architecture mode Wow64



======== C:\Users\audacity-2.3.2\audacity.exe [32-bit PE] ========

audacity.exe

    WINMM.dll [!]

        WINMMBASE.dll [!]

            msvcrt.dll [KnownDLL]

            api-ms-win-core-heap-obsolete-l1-1-0.dll [API set]

                kernel32.dll [KnownDLL]

    USER32.dll [KnownDLL]

        win32u.dll [Base]

        GDI32.dll [KnownDLL]

            api-ms-win-gdi-internal-uap-l1-1-0.dll [API set]

                gdi32full.dll [Base]

                    msvcp_win.dll [Base]

                        api-ms-win-crt-string-l1-1-0.dll [API set]

                            ucrtbase.dll [Base]

    COMDLG32.dll [KnownDLL]

        api-ms-win-core-winrt-error-l1-1-1.dll [API set]

            combase.dll [KnownDLL]

                RPCRT4.dll [KnownDLL]

                    SspiCli.dll [Base]

                        CRYPTBASE.dll [Base]

                            bcryptPrimitives.dll [Base]

        SHLWAPI.dll [KnownDLL]

        COMCTL32.dll [WinSxS]

            ADVAPI32.dll [KnownDLL]

                api-ms-win-eventing-controller-l1-1-0.dll [API set]

                    sechost.dll [KnownDLL]

        SHELL32.dll [KnownDLL]

            api-ms-win-shcore-path-l1-1-0.dll [API set]

                shcore.dll [KnownDLL]

            api-ms-win-storage-exports-internal-l1-1-0.dll [API set]

                windows.storage.dll [Base]

                    api-ms-win-appmodel-state-l1-2-0.dll [API set]

                        kernel.appcore.dll [Base]

                    profapi.dll [Base]

                    api-ms-win-power-base-l1-1-0.dll [API set]

                        powrprof.dll [Base]

                    FLTLIB.DLL [Base]

    ole32.dll [KnownDLL]

    MSVCP140.dll [!]

        VCRUNTIME140.dll [!]

    wxmsw311u_qa_vc_custom.dll [!]

        wxmsw311u_core_vc_custom.dll [!]

            wxbase311u_vc_custom.dll [!]

                VERSION.dll [!]

            WINSPOOL.DRV [!]

                PROPSYS.dll [!]

                    OLEAUT32.dll [KnownDLL]

                IPHLPAPI.DLL [!]

                bcrypt.dll [!]

            OLEACC.dll [!]

            UxTheme.dll [!]

            MSIMG32.dll [!]

        wxbase311u_xml_vc_custom.dll [!]

    wxmsw311u_adv_vc_custom.dll [!]

    wxmsw311u_html_vc_custom.dll [!]



[!] Module WINMM.dll vulnerable (real path: C:\Windows\SysWOW64\WINMM.dll)

[!] Module WINMMBASE.dll vulnerable (real path: C:\Windows\SysWOW64\WINMMBASE.dll)

[!] Module VERSION.dll vulnerable (real path: C:\Windows\SysWOW64\VERSION.dll)

[!] Module WINSPOOL.DRV vulnerable (real path: C:\Windows\SysWOW64\WINSPOOL.DRV)

[!] Module PROPSYS.dll vulnerable (real path: C:\Windows\SysWOW64\PROPSYS.dll)

[!] Module IPHLPAPI.DLL (real path: C:\Windows\SysWOW64\IPHLPAPI.DLL)

[!] Module bcrypt.dll vulnerable (real path: C:\Windows\SysWOW64\bcrypt.dll)

[!] Module OLEACC.dll vulnerable (real path: C:\Windows\SysWOW64\OLEACC.dll)

[!] Module UxTheme.dll vulnerable (real path: C:\Windows\SysWOW64\UxTheme.dll)

[!] Module MSIMG32.dll vulnerable (real path: C:\Windows\SysWOW64\MSIMG32.dll)

