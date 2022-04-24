# filename
 to $n_WO-1     $bix_qty[$i]=_StringBetween($WorkOrders[$i],"&lt;quantity>","&lt;/quantity>")[0]     $bix_filename[$i]=StringRegExpReplace(_StringBetween($WorkOrders[$i],"path=""",""">")[0], "^.*\\", "") Next  _ArrayDisplay($bix_qty,"") _ArrayDisplay($bix_filename,"")
