# CBT1054
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE1054 is from Paul Lemons and contains a way of determining *   FILE1054
//*           whether a TSO user is using a password or a pass-     *   FILE1054
//*           phrase.  His installation is switching all their      *   FILE1054
//*           TSO users from passwords to passphrases, and they     *   FILE1054
//*           want to be able to monitor whether a TSO user has     *   FILE1054
//*           switched to passphrases, or they are still using      *   FILE1054
//*           passwords.                                            *   FILE1054
//*                                                                 *   FILE1054
//*           The PARMLIB settings, described in member IKJTSOXX    *   FILE1054
//*           are very important to set, in any case.               *   FILE1054
//*                                                                 *   FILE1054
//*           It seems that Paul's software is dependent on the     *   FILE1054
//*           installation having the VPS product from Levi, Ray,   *   FILE1054
//*           and Shoup.  See $$NOTE02 in this pds for particulars  *   FILE1054
//*           about Paul Lemons' installation (an LRS shop).        *   FILE1054
//*                                                                 *   FILE1054
//*           Another way to get this information is from a simple  *   FILE1054
//*           exec from John Kalinich, presented here as member     *   FILE1054
//*           CKPWPP (courtesy of Lionel Dyck).                     *   FILE1054
//*                                                                 *   FILE1054
//*           email:  Paul.Lemons@Vericast.com                      *   FILE1054
//*                                                                 *   FILE1054
//*           email:  lbdyck@gmail.com                              *   FILE1054
//*                                                                 *   FILE1054
//*           email:  jkalinic@outlook.com                          *   FILE1054
//*                                                                 *   FILE1054
//*      Partial listing from the CKPWPP exec (illustration):       *   FILE1054
//*                                                                 *   FILE1054
//*           LBDYCK   PASSWORD   NOPASSPHRASE                      *   FILE1054
//*           LBDYCKX  PASSWORD   NOPASSPHRASE                      *   FILE1054
//*           LBDYCK1  PASSWORD   PASSPHRASE                        *   FILE1054
//*           LDW      PASSWORD   NOPASSPHRASE                      *   FILE1054
//*           LIAMD    PASSWORD   NOPASSPHRASE                      *   FILE1054
//*           LLA      NOPASSWORD NOPASSPHRASE   (a system task)    *   FILE1054
//*           TRIDSS   PASSWORD   PASSPHRASE                        *   FILE1054
//*                                                                 *   FILE1054
```
