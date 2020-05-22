print('=-' * 20)
print('PROGRAMA PARA QUEBRAR VÍDEOS EM FRAMES')
print('=-' * 20)

arquivo = str(input('Digite o nome do arquivo de vídeo: '))
ext = str(input('Digite a extensão do vídeo: '))
quadros = int(input('Digite quantos quadros por segundo você deseja? O Default é o máximo, representado por 25 quadros por segundo: '))

'''Comentário:
Instruções iniciais, para 
Esse argumento -r 25 é qtos frames/segundo vc quer extrair. o padrão dos videos é q tenham 25 frames/segundo, portanto nesse comando é extraido todos os frames

-qscale 0 esse argumento garante a qualidade máxima'''

print('O Código que dese ser executado no prompt de comando é: \nffmpeg -i {}.{} -y -an -qscale 0  -r {} frame%03d.jpg'.format(arquivo,ext,quadros))
