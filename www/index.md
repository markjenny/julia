[julia]: https://github.com/wgtdkp/julia
[wgtcc]: https://github.com/wgtdkp/wgtcc
[juson]: https://github.com/wgtdkp/juson
[nginx]: https://nginx.org/
[lighttpd]: https://www.lighttpd.net/

# _Welocome to julia_
_[Julia]_ is a lightweight high performance http server(imaging that it is tiny nginx).

The repo is under developing yet. Full Supporting for [RFC 2616](https://www.ietf.org/rfc/rfc2616.txt) is only in completed now. At least, it works and can serve static resources and pass request for dynamic resource to backend(this site is powered by _[julia]_).

I have suspended this project for a few months after it has worked.

Now i restart it, planning to complete the supporting for RFC 2616, and then build a simple script language to serve dynamic resources(imbedded in the server directly).

## TRY IT
Fork the repo, install it following the instruction. Modify the config file to your port and document root.

## WHAT ELSE
Development of _[julia]_ is interrupted by another project:_[wgtcc]_. _[Wgtcc]_ is a simple yet powerful C11 compiler. As you may guessed, **server of this site is compiled by _[wgtcc]_!**

So, to make things cooler, i may continue making my script language:)

If you are interested in my projects, follow [me](https://github.com/wgtdkp), or watch these projects on GitHub, or email me for detail issues: _wgtdkp@163.com_

### REFERENCE
1. [nginx]
2. [lighttpd]
3. [juson]

_Powered by julia/0.1_
