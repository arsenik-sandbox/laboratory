# Static Analysis



<table>
    <thead><th>Table of Contents</th></thead>
    <tbody>
        <tr><th><a href="#bintext">Bintext</a></th></tr>
        <tr><th><a href="#cffExplorer">CFF Explorer</a></th></tr>
        <tr><th><a href="#peStudio">PeStudio</a></th></tr>
        <tr><th><a href="#peid">PEiD</a></th></tr>
        <tr><th><a href="#resourceHacker">Resource Hacker</a></th></tr>
        <tr><th><a href="#pe-bear">PE-bear</a></th></tr>
        <tr><th><a href="#apktool">apktool</a></th></tr>
        <tr><th><a href="#detectitEasy">Detect it Easy</a></th></tr>
        <tr><th><a href="#strings">Strings</a></th></tr>
        <tr><th><a href="#floss">FLOSS</a></th></tr>
        <tr><th><a href="#hashMyFiles">Hash my files</a></th></tr>
        <tr><th><a href="#exeInfoPE">ExeInfo PE</a></th></tr>
        <tr><th><a href="#hxd">HxD</a></th></tr>
        <tr><th><a href="#fileAlyzer">FileAlyzer</a></th></tr>
        <tr><th><a href="#ssdeep">SSDEEP</a></th></tr>
    </tbody>
</table>

<table>
    <thead><th id="bintext">Bintext</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>Bintext</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://www.aldeid.com/wiki/BinText">BinText - aldeid</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>Finds Ascii, Unicode and Resource strings in a file</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>Finding unpacked/unencrypted strings in a file</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>strings</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="cffExplorer">CFF Explorer</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>CFF Explorer</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://ntcore.com/explorer-suite/">Explorer Suite – NTCore</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div>
                    <ul>
                        <li>shows header information</li>
                        <li>import functions</li>
                        <li>hex editor</li>
                        <li>quick disassembler</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>General information about a PE file</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>PEiD, PeStudio</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="peStudio">PeStudio</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>PeStudio</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://www.winitor.com/">PeStudio - winitor</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div>
                    <ul>
                        <li>Checks the sample on VirusTotal</li>
                        <li>Import functions</li>
                        <li>Strings</li>
                        <li>Libraries</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>General information about a PE file</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>PEiD, CFF  Explorer</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="peid">PEiD</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>PEiD</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://www.aldeid.com/wiki/PEiD">PEiD - aldeid</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div>
                    <ul>
                        <li>Detects packers, decryptors and compilers</li>
                        <li>Different scan modes</li>
                        <li>Normal: Entry point and included signatures</li>
                        <li>Deep Mode: Increased detection ratio</li>
                        <li>Explore all the currently running processes</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div>
                    <ul>
                        <li>Detect which packer was used to pack the binary</li>
                        <li>Detect known decryptors</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>CFF Exporer, PeStudio</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="resourceHacker">Resource Hacker</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>Resource Hacker</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="http://www.angusj.com/resourcehacker/">Resource Hacker - angusj</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div>
                    <ul>
                        <li>Viewing and editing resources in executables</li>
                        <li>Add - modify - replace resources (strings, images, dialogs, menus, VersionInfo and Manfiest resources)</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div>Analyze resource files in binaries</div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div></div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="pe-bear">PE-bear</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>PE-bear</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://hshrzd.wordpress.com/pe-bear/">PE-bear</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>Its objective was to deliver fast and flexible “first view” tool for malware analysts, stable and capable to handle malformed PE files</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div>
                    <ul>
                        <li>Analyze PE files</li>
                        <li>Rebuild Imports Table</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div></div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="apktool">apktool</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>apktool</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://ibotpeaches.github.io/Apktool/">Apktool - A tool for reverse engineering 3rd party, closed, binary Android apps</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>APK Files (binary Android apps)</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>A tool for reverse engineering 3rd party, closed, binary Android apps</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div>Analyze APK files</div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div></div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="detectItEasy">Detect it Easy</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>Detect it Easy</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://github.com/horsicq/Detect-It-Easy">Detect it Easy - NTInfo</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>Detects packers</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div>Detecting packers like UPX etc.</div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div></div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="strings">Strings</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>Strings</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href=""></a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Any file</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div><ul><li>Free</li></ul></div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>Finds ASCII, Unicode strings in a file</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>Quick check if there are strings in file</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>Bintext, FLOSS</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="floss">FLOSS</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>FLOSS</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="fireeye.com/services/freeware/floss.html">FLOSS - FireEye</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Any file</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>Finds ASCII, Unicode strings in a file</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>Quick check if there are strings in file</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>Bintext, strings</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="hashMyFiles">Hash my files</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>Hash my files</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://www.nirsoft.net/utils/hash_my_files.html">Hash My Files - Nirsoft</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Any File</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>Calculate MD5/SHA1/CRC32 hashes of your files</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>Calculating the hash of file and compare it on VirusTotal</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>md5sum, sha1sum, ...</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="exeInfoPE">ExeInfo PE</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>ExeInfo PE</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="http://www.exeinfo.xn.pl/">ExeInfo PE - A.S.L</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Windows EXE/PE files</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div>
                    <ul>
                        <li>Packer detector</li>
                        <li>Compressor detector</li>
                        <li>Unpack info</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>Get a short overview how the file was compiled, packed, ...
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>Detec It Easy, PeID</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="hxd">HxD</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>HxD</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://mh-nexus.de/en/">mh-nexus</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Any File</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
           <td><div><ul><li>Hex editor</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>View/edit the file in HEX mode</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>Any hex editor</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="fileAlyzer">FileAlyzer</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>FileAlyzer</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://www.safer-networking.org/de/products/filealyzer/">FileAlyzer - Spybot Anti-Malware and Antivirus : Spybot Anti-Malware and Antivirus</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Any File</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div>
                    <ul>
                        <li>Shows details about the file</li>
                        <li>md5sum</li>
                        <li>sha1sum</li>
                        <li>MZ header</li>
                        <li>PE header</li>
                        <li>Upload to VirusTotal</li>
                    </ul>
                </div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>See details about the file</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div>PEiD, CFF Explorer, PE Studio</div></td>
        </tr>        
    </tbody>
</table>

<table>
    <thead><th id="ssdeep">SSDEEP</th></thead>
    <tbody>
        <tr><th>Tool</th>
            <th>SSDEEP</th>
        </tr>
        <tr>
            <th>URL</th>
            <td><div><a href="https://ssdeep-project.github.io/ssdeep/index.html">	ssdeep - Fuzzy hashing program</a></div></td>
        </tr>
        <tr>
            <th>Target</th>
            <td><div>Any File</div></td>
        </tr>
        <tr>
            <th>Cost</th>
            <td><div>Free</div></td>
        </tr>
        <tr>
            <th>Description</th>
            <td><div><ul><li>SSDEEP is a program for computing context triggered piecewise hashes (CTPH). Also called fuzzy hashes, CTPH can match inputs that have homologies.
Such inputs have sequences of identical bytes in the same order, although bytes in between these sequences may be different in both content and length.</li></ul></div></td>
        </tr>
        <tr>
            <th>Useful for</th>
            <td><div><ul><li>Fuzzy hashing</li></ul></div></td>
        </tr>
        <tr>
            <th>Similar Tools</th>
            <td><div></div></td>
        </tr>        
    </tbody>
</table>
