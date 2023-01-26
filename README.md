# Python-Program
def longetscommonstring(a1,a2):
  m = len(a1)
  n= len(a2)
  result = 0
  end = 0
  length = [[0 for x in range(n+1)] for y in range(2)]
  row = 0
  for i in range(m):
      row = row^1
      for j in range(n):
          if a1[i] == a2[j]
  length[row][j]=length[row^1][j-1]+1
              if length[row][j]>result:
                  result""
              return s1[end-result+1:end+1]
  a1 = "abcdefg"
  a2 = "dfgedhi"
  print("Longest common substring:",longetscommonstring(a1,a2))
    
