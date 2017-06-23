---
layout : default
title : Julia Downloads
---

# 現行版本 (v0.6.0)

我們提供多種方式讓你執行 Julia：

* 在終端機中使用內建的 Julia 命令列指令。
* 以瀏覽器前往 [JuliaBox.com](https://www.juliabox.com) 使用 Jupyter notebooks。 無須安裝 -- 只需以你的瀏覽器前往該網站，登入並開始從事計算工作。
* [Julia Computing](http://juliacomputing.com) 的 [JuliaPro](http://juliacomputing.com/products/juliapro.html) 是一個「內含電池」的 Julia 發行版本。它包括了 [Juno IDE（整合式開發環境）](http://junolab.org)，[Gallium 除錯器](https://github.com/Keno/Gallium.jl)，以及作圖、最佳化、機器學習、資料庫等為數眾多的套件（需經過註冊）。

作圖能力是由外部套件所提供，像是 [PyPlot.jl](https://github.com/JuliaPy/PyPlot.jl) 及 [Gadfly.jl](http://gadflyjl.org)。
將大部分 Julia 的作圖功能後端整合起來並有良好文件說明 API 的套件是 [Plots.jl](https://github.com/JuliaPlots/Plots.jl)。 請閱讀[作圖說明](plotting.html)來安裝作圖套件。如果你是使用 JuliaBox，所有這些作圖套件都已事先安裝。

## Julia (命令列版本)
<table class="downloads"><tbody>
<tr>
    <th> Windows 自我解壓縮檔 (.exe) </th>
    <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x86/0.6/julia-0.6.0-win32.exe">32-bit</a> </td>
    <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x64/0.6/julia-0.6.0-win64.exe">64-bit</a> </td>
</tr>
<tr>
    <th> macOS 套件包 (.dmg) </th>
    <td colspan="6"> <a href="https://julialang-s3.julialang.org/bin/osx/x64/0.6/julia-0.6.0-osx10.7+.dmg">10.8+ 64-bit</a> </td>
</tr>
<tr>
    <th> 通用 Linux 二進位檔 </th>
    <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x86/0.6/julia-0.6.0-linux-i686.tar.gz">32-bit (X86)</a> (<a href="https://julialang-s3.julialang.org/bin/linux/x86/0.6/julia-0.6.0-linux-i686.tar.gz.asc">GPG</a>)</td>
    <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x64/0.6/julia-0.6.0-linux-x86_64.tar.gz">64-bit (X86)</a> (<a href="https://julialang-s3.julialang.org/bin/linux/x64/0.6/julia-0.6.0-linux-x86_64.tar.gz.asc">GPG</a>)</td>
</tr>
<tr>
    <th> 組建給其他架構的 Linux </th>
    <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/arm/0.6/julia-0.6.0-linux-arm.tar.gz">ARMv7 32-bit hard float</a> (<a href="https://julialang-s3.julialang.org/bin/linux/arm/0.6/julia-0.6.0-linux-arm.tar.gz.asc">GPG</a>)</td>
    <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/ppc64le/0.6/julia-0.6.0-rc3-linux-ppc64le.tar.gz">PowerPC 64 little endian</a> (<a href="https://julialang-s3.julialang.org/bin/linux/ppc64le/0.6/julia-0.6.0-rc3-linux-ppc64le.tar.gz.asc">GPG</a>)</td>
</tr>
<tr>
    <th> 原始碼 </th>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v0.6.0/julia-0.6.0.tar.gz">Tarball</a> (<a href="https://github.com/JuliaLang/julia/releases/download/v0.6.0/julia-0.6.0.tar.gz.asc">GPG</a>) </td>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v0.6.0/julia-0.6.0-full.tar.gz">包括相依檔案的Tarball</a> (<a href="https://github.com/JuliaLang/julia/releases/download/v0.6.0/julia-0.6.0-full.tar.gz.asc">GPG</a>) </td>
    <td colspan="2"> <a href="https://github.com/JuliaLang/julia/tree/v0.6.0">GitHub</a> </td>
</tr>
</tbody></table>

如果你在安裝 Julia 時有遭遇困難，請參閱 [platform specific instructions](platform.html)。供本發行版本的檢查碼有 [MD5](https://julialang-s3.julialang.org/bin/checksums/julia-0.6.0.md5) 及 [SHA256](https://julialang-s3.julialang.org/bin/checksums/julia-0.6.0.sha256) 兩種格式。

如果你無法執行此處所提供的下載檔案，請前往參閱 [Julia 專案的議題](https://github.com/JuliaLang/julia/issues).

# 較舊的版本

給各平台的舊版 Julia 在 [較舊版本發行網頁]中(http://julialang.org/downloads/oldreleases.html)可供下載。

對於 Julia 0.5，僅有支援錯誤修正版。比 0.5 版舊的發行版本目前已無維護。

# 夜間特快車版

有如刀鋒邊緣的開發中最新版本 Julia 二進位檔可供你預覽最新的進度。夜間特快車版是提供給開發者預覽的，其用意並非供給一般用途。你應該預期有許多套件並無法以該版本運作。建議大部分的使用者使用最新正式發布或以上的 Julia 版本。

<table class="downloads"><tbody>
<tr>
    <th> Windows 自我解壓縮檔 (.exe) </th>
    <td> <a href="https://status.julialang.org/download/win32">32-bit</a> </td>
    <td colspan="2"> <a href="https://status.julialang.org/download/win64">64-bit</a> </td>
</tr>
<tr>
    <th> macOS 套件包 (.dmg) </th>
    <td colspan="3"> <a href="https://status.julialang.org/download/osx10.7+">10.8+ 64-bit</a> </td>
</tr>
<tr>
    <th> 通用 Linux 二進位檔，供 X86 平台 </th>
    <td> <a href="https://status.julialang.org/download/linux-i686">32-bit</a> </td>
    <td> <a href="https://status.julialang.org/download/linux-x86_64">64-bit</a> </td>
</tr>
<tr>
    <th> 通用 Linux 二進位檔，供 ARM </th>
    <td> <a href="https://status.julialang.org/download/linux-armv7l">32-bit (armv7-a hard float)</a> </td>
    <td> <a href="https://julialangnightlies.s3.amazonaws.com/buildog/bin/linux/aarch64/julia-latest-linuxaarch64.tar.gz">64-bit (armv8-a)</a> </td>
</tr>
<tr>
    <th> 組建給其他架構的 Linux </th>
    <td colspan="3"> <a href="https://status.julialang.org/download/linux-powerpc64le">PowerPC 64 little endian</a> </td>
</tr>
<tr>
    <th> Fedora/RHEL/CentOS/SL 套件包 (.rpm) </th>
    <td colspan="3"> <a href="https://copr.fedoraproject.org/coprs/nalimilan/julia-nightlies/">32/64-bit</a> </td>
</tr>
<tr>
    <th> 原始碼 </th>
    <td colspan="3"> <a href="https://github.com/JuliaLang/julia">GitHub</a> </td>
</tr>
</tbody></table>

---

# 下載驗證
對於每個作業系統平台下之所有的 Julia 二進位檔發行版本，均以傳統之加密方法進行保全。macOS 及 Windows 的發行版本在進行安裝之前，會以該作業系統的憑證驗證。通用型的 Linux tarball 檔及原始碼 tarball 檔是透過使用 GPG [這個金鑰](../juliareleases.asc) 簽署。Ubuntu 及 Fedora/RHEL/CentOS/SL
發行版本在安裝時，是以套件管理程式來驗證他們各自的金鑰。
