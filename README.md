# Binary-Search-Tree
binary search tree write the search algorithm

IsThere(tree, item)
if(tree is null)
  RETURN FALSE
else
  if(item equals info(tree))
    RETURN TRUE
  else
    if(item < info(tree))
      IsThere(left(tree), item)
    else
      IsThere(right(tree), item)
    
