clc;
clear;
close;
load cape
X = conv2(ones(8,8)/64,cumsum(cumsum(randn(100,100)),2));
surf(X,'EdgeColor','none','EdgeLighting','Phong'...
    ,'FaceColor','interp');
colormap(map);
caxis([-10,300]);
grid off; axis off;
