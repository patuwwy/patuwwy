<ul class="backg">
                    <li class="l1"></li>
                    <li class="l2"></li>
                    <li class="l3"></li>
                    <li class="l4"></li>
                    <li class="l5"></li>
                    <li class="l6"></li>
                    <li class="l7"></li>
                    <li class="l8"></li>
                    <li class="l9"></li>
                    <li class="l10"></li>
                    <li class="l11"></li>
                    <li class="l12"></li>
                    <li class="l13"></li>
                    <li class="l14"></li>
                    <li class="l15"></li>
                    <li class="l16"></li>
                </ul>
<style>
.backg {
            -webkit-perspective: 400px;
            -moz-perspective: 400px;
            -webkit-perspective: 400px;
            -moz-perspective: 400px;
            perspective: 400px;
            position: fixed;
            top: 0%;
            height: 100%;
            width: 100%;
            left:0;
            margin-top: 0;
            opacity: 0.4;
            z-index:0;
        }

        @media screen and (min-width:620px) {
            .backg {
                -webkit-animation: hueShift 120s -1s linear infinite;
            }
        }

        .backg li {
            display: block;
            height: 500px;
            width: 500px;
            position: absolute;
            top: 50%; left:50%;
            margin:-250px auto auto -250px;
            background: 50% 50% no-repeat; background-size: 100%;
            -webkit-animation: move 4s infinite linear -4s;
            -moz-animation: move 4s infinite linear -4s;
            animation: move 4s infinite linear -4s;
        }

        .backg li:nth-child(4n) {
            background-image: url('data:image/png;base64,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');
        }
        .backg li:nth-child(4n+1) {
            background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMgAAADIAgMAAADQNkYNAAAAA3NCSVQICAjb4U/gAAAACVBMVEX///+SbW1tSUnopdc8AAAAA3RSTlMA//9EUNYhAAAACXBIWXMAAAsSAAALEgHS3X78AAAAHHRFWHRTb2Z0d2FyZQBBZG9iZSBGaXJld29ya3MgQ1M26LyyjAAAABZ0RVh0Q3JlYXRpb24gVGltZQAwNC8wMS8xM9I8xO0AAAs5SURBVGiBrZrNbty6FYApYlRMuXIAq4uupgFuMeFT0EWyuSs5EIV4VukiQKOnUAco0M7qorAMXK+EQcaQ+JQ9h38iKWnsACWCWHH0zfnl4SE5hPzfxp5TQm5/AqA9V+wf5PHnxIzfJHn8GTGEsE6y7uEryW5u3sxk96r7LggRxdvlNBc5wA9RvpmgTQcIbQtA3qrbf6X8QlhbVIS8VVChkUcpRf5WJJeyqpWUMpNl8QpUmR8ZvF0ZpLqKbG6dGhoZ4S8pClle8cBG5sI+wst1J++kJEUpq80qkslPJEC0CFIIualWRGh1jJSbQuoBbsikqApZiOtILixS9b/Iu3tRvcvJkpwMPxI+Fx/vjQxZD4XcCviUjMgFMbkUEAODlFYviMy/VLtqOrgX1M41UuH7nxB5ou06kpV5DroZHdGODJEfbBVAKQUGQT87RDaKXkMqfK1ySEk+aOQKod1VZjfuuSJ/hF+oq4g2YHqusAB0TX8N0X4VAaK6qvv1KnKTT1LAmK9jI79UdLiGuNhnRuKX8UGKkl1HiEFyyA14+g0c9pWfVs3PQiS7x6fduQNErdqiAygwLgJML1FHpp46wa2Q7RzR0cAZm1eQNRqplVJ/O18Ni1YMpmyBUqSOovrct/h7tuXt7GU9tcFNME8qkIIhqo8QeWMJXciBTFoEcybHP4C0XB3tqwtIfic8AlL0bJFcqcE6TPFZeEwlspM3tz//Csagx1pGFf33TLGS2LQMBroMNepbNtCZ+Vn5kZiEmSEtUT1dcDXU3QUxRgpVvVqoGBCKbAVRJ/xrITkLFJMijfKjT4vGDcEZldrixOjxPjGnzHQOX0NSS0SxjHBPDPsEgZcrqOwp8imQMqQIODkXqfVdEyJxBdRLWzZz2NicAibWDNMQvJYg9eUwAadEM3yhvPVpacfhEiiWzhhdWYlLfh/IcbLjSHicM4iIENEPgQyCE3NJysY7WT/UE4ICQiTTH1+RTfHJIVmC9IRFhdYgJSSNW1Ml6WJkIIyFtkCxA+S+CnxMfpcXGbhYEabCspmZqiWDdMmaQ4SAUmoINYNVOIk74zNkt9tGyHxuARIYo3UKk6yCViiOIgi4mB8BQiJEihiBzx9DJJ3577B7Mv6tQin1OMUf9QqcLKFNE8ZppSEemgRhScIUOluw6H+2HVXTqBdQzGcy6rXdxRkmEBHyc28RpeoRDHr2yDZexRxCRNNyZwr04pcpLPukXOYl1P0M+s2sISedXIAcuiDFZm6+K7GfAnPyhvhw1FGKqXMkJLtzfXPGaWdNUTo2xxUhmV7A9M6L/2eaJ2hKGyZZZL1FcUWUU8xh5sNi6UakWDF1plzJSQyqw5Y1y+78Y686g9gYwuq1bIwXQtr3BvFhpydnSoTcTAihU1oa39IA2fnX3gU4VTEyEONolMEmQWH73zpjHMIUdz7mEzJ1/8whfvUidPDWBx6YdrVQekYZIY9sZ/zc73W1tPls04W1dEK0xw4wmRkx0Ry4nmJmWc48wk/F4XdfYhr19DTK5myNUkztHOLCAggt/txZREFouvryTYUDXNCGCCd7muvc107uYJLVsFieJ6L3iB0cPJlvL64odSPMS0ADZEjXGBScfeucFDCnk/E0GwinkWIa8dVyjLPAjHYfIxzN84hzQ8S0Tq8JadsZ8qBiOakt6lw4xLEyRuL5jFF+kQly+Na8glxkMg6jM6bXiTOEjZwpJg8J0oxOsx9tbzPADTdjE0L54v9I/VxziM3YQ4Qc1JMlxtI4KEKY/q8mQqay3BmkDzosNy8SzbBDRsvHyjgo6GOZr6WJMVgv+xwRijuSNkTUMoL1khT85RHzHh4nxbhHvsfIAP/zQTbPv4HqcRfnECjdslahlPegszzUWEt4lGNOsQvE7mALk/ZyS46Hr7pTH7BwBojdC0CsuwhpOnZ8+LvEtpufo9h761GpQ6jYIz3pB6F1D4RsnSkw56V6whMbq1h1ht9UuGrxKfasnaRoxdTLxafNAZa/izntQsTmPhZ0t/Jc5Ghy0SEP8uFXQDKLKI/4taozuTgGmYaWlYBQPWFMJHk/LW/Ytj0d1CX0mcJjOHByS70YfuyPAXJ4PkRpA0hFbjcmEoC05sFLGQ+2CgXBHKGN2iCyRc2oRTzxvbGdy4TAqG9cUjG1DZxlEGXX4rhulG6CUL1TjpBaXdRcikUoBN9srkPEF7olKbiIm2OJAKkDOELccWJrl/MJcWXu0sSTsyo9MvSRMb5m1cvGEHJU/S5GJgVjAjYq1gEml7majTopGtKeNG3djGEDP8VI9+xC74h7WyJc9sPqrd/0oHexz2jXG9js51DP9JtT87mG2AMmCj/MRJ78/SpiYzPMaubkBttNUdP84eaPoU5BI4mvNt1Uaz76bmowJCGnyQzrM0CesQ5aF+cu/NyxR5Yi3xHxRnmk961fGstLB20VdD7O2+KTsOF3S3JghBHX1SMk3LPLm1q47nta+Ca9zMp0qZVevccu9BcJm6twasYapkhvzxFfQ4RHBvUqMiYI9Ib2buX9GiITxQCx5/3qxK4hflZCMrq2ersmpkuMYcPUia8gz4kxrN+4e6L9qv3fIsUo7FXt04IpL6bgDA4xZu/dzo0tIJdOlzWtGR4dZlo7fnu7joymfe1MfbEv/mGo4AnXMr5khnxwi1Out1K4YOb9LRRbRmmbViUjpTnYzlHgYWCGy7K8oClMn+XMiYvEls9F8uYGD5nxaMDm10yzEYTUmP+djQseFwuNoBf4sJ/nJYYdavSzRQSeapT+UIxhw5giT7pngN7EaGb1w7MXgyz47OmiEZuW5vikLHPxSyXMTCM7j9gHfCVdzKSQ5V907sD6t1ceYYzjPwyiUkR8sEg/qcW3iFCKn68O6dJUkU4jTA2e6AeQOAyUoE7j4SXdN1gkSuMenddv9fnC5fAUIPo8rOz1pN4lCDMFEFq/ugmQrMI49iY/I4Ri/82sszxSQTgwOGJnpg07TUhrtxgD3jzJ2iOFOaEVdqZtaYiYEjuY/aJXDN8r5HQHtFD5BnNS+iqCDb7tf38k57GYJjJAmH2/nxKmS059S7xJlEGtwQW8hUUd3qXAnI9K/jONOxE5pKdHIDPxnkHPti1Tx3b/pzxFNkRfwlpiB3XzOMDSybFJ2UJ/zqcTXIfg3bCr4WTbM3uawczpSUvy2Hg0u8Cr3o23Hl7S3SzTayEicoboY2pfw/0Z9p6rLXTqC3cE9mpxst4vtOhuWHZmx/fmCqScTqw423oYVkNF0oN1jQQe9ke4Wz1XtNdSzQDZZCHiRCAyML19mCP2IigaVO0wluYMPDUGX8hmCB80YtqUBfvJ/IYb7zK5R5xm1g/aVbOvU9BeVw57cqKRe3vib5DbOQKJhtsge6ClLdB/HJIvmH/W50a4a7SIiKRkKQF26C0tO7VOMVhWqvwOv3qw8u0GMx+JvZvICvQsVLwMbxnMdkTMPKYrjENQDCC35nZZI3mK7Lmtljbf8LM3+qS5WFFst3OIzTiYlmWhkXwF4b3ZJuzc1Yw2X2wMcr+EwEbT1CZiu+fCf7S+zJuZTvSSeTQuc++5yBU+Y1KEmHq2Ywmib1pWvtuBoQFBPvr2tY9RZU0HVn6z2bZfViCYWRnm5yriI6m/3aGRAhUTK4rRo0EwlrmfVzk8L39/xOjVU0CoMUXeWwS/ELSqmL7+It4Ug5QgrVj1mEb2rTYBZ4t9kAuzyw1zWNITrZkoC4NU2cLsmgYkzbk3muGXYIi7YL6CQJfZ9tFv8nU7zBggkeMz0CJfTONgUFhmzey3owruNFZGz7DGeuVME/7a2HO28/9Y/0ZTOBa+lRGO/wHzQzJ0knkcBQAAAABJRU5ErkJggg==');
        }
        .backg li:nth-child(4n+2) {
            background-image: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMgAAADIBAMAAABfdrOtAAAAA3NCSVQICAjb4U/gAAAAFVBMVEX///+HZGLevbjDoZ2HZGJILzI4HSGJCC67AAAAB3RSTlMAVf//////HfiUcwAAAAlwSFlzAAALEgAACxIB0t1+/AAAABZ0RVh0Q3JlYXRpb24gVGltZQAwNC8wMS8xM9I8xO0AAAAcdEVYdFNvZnR3YXJlAEFkb2JlIEZpcmV3b3JrcyBDUzbovLKMAAATN0lEQVR4nM2cS3ejOrbHsVtk7K5L7thHSWp+s8gcbPCYpBBj91lwvv9HuPslaUtgJ6crvVarKvEjDtKP/35JghTFf1nbNf+xQ+/DM3P4z3Vi6aFti923H9sYk3RiqsJ8eydF0ySd7Nqm/fY+1iSHKvzwoL7/XmuSTlpo4Uet/sBvtZSkghZ+VKnvv9ka6QR72QFIE35CJLvv0IhUMWZvn+mlAikqlMN8CwkZWGOPbGfB3z1U+13WBjT2me0s+Duqc+DHb+ql2SZp6aG59VtfamV4BpqIwwQSw4YmPP9mc84NBfzn1mDDJylJU7S/o0m5LEtZXuGRXhpq4DQpSWV+CwT7KUpXOnnRtAyTkrTtb0uyYOPn1piKPKZKSX7ftkrQhUiGvW2FJEiw+xYQ7GW5ooUty97i+ScSP3LzPSCIAsI0aMr7llBw/PKz75GkQAQa/XIt9qau0LSiNVVbmvxNS2vQN5yD0fcojCVRYPhn9I1CGVeC0mwe62YjvwD7MjMZ2Z/2uaoNDr+uMIME20pR/q7PkDGB16OFgbvYIzDQyM/i6G2xRklJvlChIcrCbTaAYnncdV17AoWyLmHMFys0JKEGurygKshxPnsxtIGtjWz3xaQZUGbIJ9aaWyQHlCj/ZXj3a3GNTQuEgXxiWRFECSyaKf/dLzsR2ReR7DEzMkmFKJ4mtmzQ5qvxYBAQN/QnyIxiWvi1hslRdsry7vGUhbcutC1LJHUl39YoRZVYk+K7p4wbBufbL2uP/xAAFGWDJJMgvnPXXZbY/vzT/lmgYdXewNYkmQSR5GZlhinRxfZhT67xdnXmJ8WKI9GFOZriTmUGmUSTLC9gYp6kruvoLHdJ8OGet5QFk/QRJyO5L8rOC7LhQgqFm5ln/xSG/4r2f4ckzTX++e1OfNjyXs8k+/25vckRSHbac+4GsBC2iGS2Lzh++4yWdYNjrq5FAf/F3b8SuAaEGQYh+bBP59g2IHrXun7AM+BJvtAHs1zB642kxjq2NcXyOD/ix8sF65vc1OLI8zdKR6Uwu/0pIclRRLb3kqtn17/fiMDX7LUhEOYpl1db13dRKgIpsOQsr/MtScr05VBQXuSzXLoTDN/eFaVtSvowkA/v7Q2SrJMruwr+AIu71+daw2w6CejBPnW9qYnqpCESTiV4iqGT09P59JSRZDzBt5y7bV1RFCobZVA4uz4Cia1fnzOSDKgIgXuW1xvLMNG8mlCnEAp2cgJBnnJJ/GMH/3jkhq2MNXIbMNeAEisuNrDj3r4mfiIIgaTzGrQoY7mItS3rTvqA0jSnwU0wpIkmKHu7t+e1x0eiruPABUd2bixKJnFbFqYnu84sDkbiyMBAEFuvSOqoSdcxCoST5QoGIEFgy1fKMNe9NNMwEQm0wdozKKKchAi0tzAJojyiiBKEUZu0ByxdZaYLvY0oH1JQaCT/SD2+1qVkxSDQ+mBaM4ayeeUrYFElWdjDNDVAcCGQoZ+OBHE6pyjndkUCT7yPtGKbWUTEvEGz9hJnCgBQEse4jIbUeM1JVNESSDpAmefqEQTh9njNQNg3mskVDwCB5SOQNKdjc143ti7vKQGEwvF727/HyiAjMTMldShUSIxnihJQz5uqXrXU4zv1iKp4H0NdchJiGSg3FNN0JNuamkbqk1U6wcdzJySdB0IUTwFMKQnR+JR+jbFuhIQ9rkBEE2ECTTqvjCrWZnL7VS9YnXDEukzS3t/b8/RriyUwddi8icVC7Z1elKuMG86nGSOLq4FnQxV66NjhuUnE8g1frX0+VvGNO3mUCUjWKOQn0DoBIZgMxUkxnLYyDKLE8lc+Wr0hzXbrdGMTUyyHzZRSRhYOXL5dNnyFgHQnbYaCamxNTqDwjbkk9pdKovxGCRLcPpLgERNRqMcSjMtnRQ2SyaFsrDsrECy3hjaOLTcsXiwtwe1lxusYZGT7WoetYGKKBD0j+jvWk/mZakIjDiFpVyRddJGzBgFPIc+IcWtYoRR74xvNSPhzL9WaBHwDvvix6yJJ38+pn3CBcAeFALCUv6w04UMiEnwpErCqvldeQq3IiuxAYgIJJPZX9PjUumj45Oz8ylvYstGwMs5ZioRk+ni6gOeff22QtGRapJHD12PXuVWj+jMTxnDJNRtvWx/P49sqbnEnCILiwMvHZe67GbNi3uZDRmKFxkFO9LZlSZLMy6M1CUnbo6GPWyQDzFg0yt4LgxBL8PTx7e1GuGJvr0WNbU2uZWpje69L9PYPqlMu2yBiZN6ylCS5hSmU/ZH8nnM9GNYL8Lzkeqwir3cUIAma0LNkQSPphCMYynKxP5HlaR14u62WDH7sWzdWmbeoTnjfqpzNnicBW3kkA6HXiWUhWHvdJCmOhaBA5m1sL7qs03uXwAjaqFjYLOJrneaPwV3AHOyzN7CVLDpeBU00y9x1ytbKUnkKztq858P/PiSU+yShuRi3EpUKHb1UJyiL8Ynxtii9JgGXl8HPSNL2az1IeNUJWJgHcTftiztRXIGj7WUZwOUV5NGqF8bTvqWazAplTEi6vgqSVFColBsgRYhe3EKdkprXr1s+H0BG6LsdwvQ5i8F7q7rxBeQdl3djJn0vTgIkJWX6ak2yt5Y7IW2abdNSoswZSR+dRFb7YCo/xMss+GxxJ0JTuZct43oLIL1LKKKnQO8VCXKA6HcNV1kknZxol3d34uC18vjRj7yfk07GIAqcxqbBaU5TwpzRbxpH4TF+0QbDs6msZZI0nbzNauyJHgqlq6B8m2HS5gaTkgzYiSWgpjm27cl+WBQlwlAidOqoSpM+gsAnqFLo4f/SNAlKyZ0ccYPBvpjK7O1LZmEYc/2xXUaio1dXUckDX6uifrDHxpIy1v68XJqTFQObfjEMhVxvt0uXduJiZhy7dxh965Akr+/KgrauqCHDs5BI2dUxjde7T72kVzXw3M20zQU4q7CyH2Dwvk0fP5+8ef0S5yAUsVw8lLYtlzRaJiJd1ihmL118vLiPl+fXxFMoSKEmNUsyJhxp4/UVFGYVV7A88RiThTr4p3J6tiQkoaMvvSZZlVwdk/S8156igNXaZ2uIwL5gHRyNqyMQEIUkT9x9xTJjVUYg6zVtrBmn48Bh60Ny/MRrj94rRJR+ZV1pE02WJu+jsO4D3ZxJPgTjTVZR5Wj1Ak+xJM2tK21MYmg9OoWBcIUyNGE5grzEWpVDAOTcj7OP6bdUgdkjez1WRql97QmBbCI4Vl3Tyl04WP0Gp7z3MT2SzJGlD5oYSrCp9vti+EhB0EWIxNco8AQHCv3MXdaiaZF1cdRCRymTTVPoxMcr32ohET+hlA6D1RwLd6f06Dh6QUMnRUl0DDvuJYvIA6EISUiB4Cmj7sVbQAzCEC4lDuM5vDZpdoQISVnERqDx1fqF1GBI0M8Sz5b3yz74yAwwxgRtR5NkFXOwIMpP9PjQTtYm5RYUinA8kGWkmEUu0nfRUzoOniIItus1ySltCwb2UZQDhK8giycJhhROPT7l13NUxSMatWY2KpKq+gGR61hQevwZ3N5m0xL/myRPLBv9T0Qj9Hc0rZJQCgUC56bFdXBJKRAB3uArmBZrEIeM3/vlr8UHGU/IJBKDIadopweS56r6X4jSllE+8DvOHKMNoemEsx+Y0hTfC0kpO29FEVF2QPIHL4yBkVmSg62tG51aQ4HjoassPPK/pgmXVUaszQlkxgGNQIIMRUnXoUVJDJNgsz+pVPmwaGf4pUTpaeIKs/DZV78Y+aO/81kkEISQStWjEIIH+WAQEuYFiuhIgm9hN3CS/nIAskz4rgcBqaB/JClZkjyhhD0wzI5oVmxjT1Ma1hfqYokqjMrmYO5L4oubFKsGDKzJiSsW/ubq56SP3vHeSg8kOBRxDU+CbSTjwk3EVR94SQhflvSDiy9M+aBNPiPxyzuhjWM/JqlxuYZS5ZqDFBiId4HkQ76lU3cIJUscM5NcJhIlBuLFjCOHrnwhSl18EOqvD6xaEhL0RZeROJfXKz3CUOCKq524Rqwv2YPDh0IPLyZQnTgXohc5CbTRB1N+k43PSeSiTgZxkbBfJySBJiOZMSS6XJZEEdo7vMahgLOIs4ftOiH542RPJyHpsgYHGieRJGmBRI9BLmoo1LajqX4QxDN4/xaJ2Bcda95YrXMSD5QVXNlh1Lr9jjiAxGtTr0h6OhBud3YJB/sPa5JaR77W7W3rWfyl2ljjQk+h8Y6bJOt21cudO68Ik+Bj261Q6Fgw8MltKLJpEekCNIeuSkiwk+p/VigQUpyc9/RYIwFukCQbHLw3bBEB97ntHp7Xa1HIvyfmEQgmcTdsOxcElaCvf2CqB1PbXHjsgx1t69FEipkdX4UvJvkDv8yxOO5wX2wDZGQUZVjoM3iRgPRrYsfv7xkKpxPwkB/22J72qFFYZkyk77Y9Xq4TWBpNghsexYoEsgr4elWjRh2RtFknl/GSWBYe/S/uh2zPKBJHe2m5cTHN07nFNxgk2SBDklmSSuLzPHCM002nSR4rrclObeKDTR2KHYHUbZuiXMi2UAQoVHx293JAOaNWc3C67RrtKJ4EPvMDbKopDM14u6rKUPzp75PJIo9czM/7OjCk28zqegQE4EPX9WuboVzIR9w0wuliN3HR2+kTYUsTEcpSW1e8sqJr/QY1zLHI+z3KTCB0yBHr+ZVx4Qc6f1kGM5SKZBdJ6MoBBulqjsj+TMEJn+QsYV1y8eaFPSDhmG01Y0RUQTgYF38qzN1/VIoEh+pmOeVuzibwBIJbmtXjYxAlWZDaSXrcdfG0YTspEJzMxeX/JXj9ArqQzY04QrIpD5LuMsulqm08a9KJjT32VFF729lweqjHwTHmsM985Too0EiPVZWCQCeapOui3a6SvMPCWIEMWKiQ1sG4xJC7FATMq1JblnN0gi0W/sxSeY5rkdzU46+U4ktQDkX0P+0lUFErD8xBqNoHisnvM3sBmkQRhuu6olDepxweo5EiyesVAo155Zqco8wlcd0i9qFJkELZ7ZjCwBuXy4WzJmmyWlTzpw2OqYXPovCStZykcq5SObK4bkxSyCcT5dMonC+fQT2spHF0nUA/xZ8XG5MUEqXjewwiiWr9miOhGR9xk3FWu/+bp8scDnTSukCiuhgzkokqybQCe+/76PHr6zGYhKaqgSSbnmyQZAW2c490SUZmYXk7kCGLA9b1/6W2lcjiDSn1l3d9kcwN+2oKpQlmxtjLvGj76hep3+fMHMaRIcpbmiCJtqc6yYq4v+AdZfRmNOVRrGmF4ZYmQGK0cZ3yWgXisLj7ylceg9iGGa63NUkCpOWnKQ+BhB2NoIUskuK91I4j701NOh3qoSwmURKcHq1sxpPXBxRI+ZWQHGjVBiNWudw4W6ZTJK3PJpkyvV5Je0eWtn3nq4KmocHD0K3h5XSjk06TQDGpA1ngWYiEoCBZLu7xkT7GilD24GR4I0IKCJWPvvLwHFEpPBg80NJvd3iQy0UF5R2PQ5I8bJPsWjIuLoTDpWHCwt8XdpZ5xrXfZYG0YBa6EtlrMuKBKImU2ySoFxnGLoJ4ieTB8UotrzMaV1XDjnYzqEogFGTAgw0PNyTBVMn32SQgngtJ6Kqeq7+KCkJIiSQsA2piiGHwdxlsNJ/0d60G8SQ9g3R+5drgbU+PWJ+Ajwx0JfA07Oiy5qF4GAhqozW+szUJnvWFish+CSR4OxCGXd5cYvOS0LhaJViftk0ScXb67klwYgXOPjzEiwXEYYobIL6ZSl1urKwrJJR/ySYvNtCpohXaGIhLDpE3NOFzJu6hSVrxEx+DTRcubut6salIUQzTLUEUBhd5SROHFxQN0s8jXrI9BBSR514nfvbY5i3GYDMqkK7juDU8BDWY6t7ZSsafvJJwNTeJIpBjkuugJGHdPVt++iD3F2Qko+zOxesNDap1SQyLfeQeiElAkne8JHMEIZjHlIQkudeFvnfYzyx2CgXmH2M/ahBASTnIrD4xrtSmcpLHufpnH0gK3HxbbWTTYe5rklpU8g6e/Qb6dKIJn8yuS5cjOQ4/3NOjSDAOke1AAQ3euLY+dIVOXK7JPW9v2aIKheElaSjJ4HGHRx+4QickClpU0OSubYkMMnaPV8mfdIA5GN0hFgwLfw6qNBx3HeSR8jMPIZZGkBo/1xOQHWqC/ZYQufSvGEguDxR1UYdPPF1GLUAHP/32Nw9SssR+y7zElZsLCpq/lZ9FrSLc9ExD57e8JOgldAbLQ3bCp2l8CH7x8CkKJKGDjP7gp8RiW6jIP7nIaOIdVzx0ut+ZjwyalHdFp1Xuxo/ez+2Dx5hGTuYhOR8w9BE1IZSHArP7JylRhKCj+Ql49P2dnMxSo5Ry4wpdvEm29VluFyHSW+y8n8AIxKzVctwgCfHB37n0WQ++ZfcKBpT4F5bCxMOpWwax90/0iC3/WwA77//KPajMgnrE58OvHjuO/Ct31ePOK9+1PXya0Ldak70mio077h6mh8kQxCd58AuN/97G5h+jKuUGwnL43U7ae3/lwIwUsIpbFfwXm4rHWy291PHfbTGxbDWzeRr/dvvkD+o034Ny/w50800sn92I3nx6hP8HlurFRwr4ILIAAAAASUVORK5CYII=');
        }
        .backg li:nth-child(4n+3) {
            background-image: url('data:image/png;base64,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');
        }

        .backg .l2  {-webkit-animation-delay: -3.75s; -moz-animation-delay: -3.75s;animation-delay: -3.75s; }
        .backg .l3  {-webkit-animation-delay: -3.5s; -moz-animation-delay: -3.5s;animation-delay: -3.5s;  }
        .backg .l4  {-webkit-animation-delay: -3.25s; -moz-animation-delay: -3.25s;animation-delay: -3.25s; }
        .backg .l5  {-webkit-animation-delay: -3s; -moz-animation-delay: -3s;animation-delay: -3s;    }
        .backg .l6  {-webkit-animation-delay: -2.75s; -moz-animation-delay: -2.75s;animation-delay: -2.75s; }
        .backg .l7  {-webkit-animation-delay: -2.5s; -moz-animation-delay: -2.5s;animation-delay: -2.5s;  }
        .backg .l8  {-webkit-animation-delay: -2.25s; -moz-animation-delay: -2.25s;animation-delay: -2.25s; }
        .backg .l9  {-webkit-animation-delay: -2.0s; -moz-animation-delay: -2.0s;animation-delay: -2.0s;  }
        .backg .l10 {-webkit-animation-delay: -1.75s; -moz-animation-delay: -1.75s;animation-delay: -1.75s; }
        .backg .l11 {-webkit-animation-delay: -1.5s; -moz-animation-delay: -1.5s;animation-delay: -1.5s;  }
        .backg .l12 {-webkit-animation-delay: -1.25s; -moz-animation-delay: -1.25s;animation-delay: -1.25s; }
        .backg .l13 {-webkit-animation-delay: -1s; -moz-animation-delay: -1s;animation-delay: -1s;    }
        .backg .l14 {-webkit-animation-delay: -0.75s; -moz-animation-delay: -0.75s;animation-delay: -0.75s; }
        .backg .l15 {-webkit-animation-delay: -0.5s; -moz-animation-delay: -0.5s;animation-delay: -0.5s;  }
        .backg .l16 {-webkit-animation-delay: -0.25s; -moz-animation-delay: -0.25s;animation-delay: -0.25s; }

        @-webkit-keyframes move {
            from      {
                -webkit-transform: rotateZ(0deg) translateZ(-1200px);
                opacity:0;
            }
            20%, 60%  {opacity: .61;}
            80%       {opacity: 0.4;}
            to        {
                -webkit-transform: rotateZ(180deg) translateZ(400px);
                opacity: 0.1;
            }
        }

        @-webkit-keyframes bgColor {
            from, to {background: #00F; }
            50%      {background: #F71E00;}
        }

        @-webkit-keyframes hueShift {
            from, to { -webkit-filter: hue-rotate(0deg);}
            50%      { -webkit-filter: hue-rotate(360deg); }
        }

        @-moz-keyframes move {
            from      {
                -moz-transform: rotateZ(0deg) translateZ(-1200px);
                opacity:0;
            }
            30%, 40%  {opacity: 1;}
            80%       {opacity: 0.4;}
            to        {
                -moz-transform: rotateZ(180deg) translateZ(400px);
                opacity: 0.0;
            }
        }

        @-moz-keyframes bgColor {
            from, to {background: rgb(128, 95, 90);}
            50%      {background: rgb(38, 5, 0);}
        }

        @keyframes move {
            from      {
                transform: rotateZ(0deg) translateZ(-1200px);
                opacity:0;
            }
            20%, 60%  {opacity: 1;}
            80%       {opacity: 0.4;}
            to        {
                transform: rotateZ(180deg) translateZ(400px);
                opacity: 0.1;
            }
        }

        @keyframes bgColor {
            from, to {background: rgb(128, 95, 90);}
            50%      {background: rgb(38, 5, 0);}
        }


</style>
