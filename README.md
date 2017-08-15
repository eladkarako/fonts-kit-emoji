<h1>Fonts-Kit Emoji</h1>

You need to be rooted to copy the font-files,
into <code>/system/fonts/</code>, and the <code>fallback_fonts.xml</code> to <code>/system/etc/</code>.
It is best to make a copy of the old <code>/system/fonts/</code> and the old <code>fallback_fonts.xml</code> file.

<hr/>

best not to try to replace the entire font folder,
but move the new files into it.

Just in-case you'll do,
owner/group should be kept "root" (0) both,
permissions for the font files and xml should be kept 0664.

<code>fonts/</code> should be root (0) too and 0755.
